# Predictive Modeling of Student Academic Performance Using Integrated Machine Learning Pipelines

## Abstract
This project leverages machine learning techniques to predict student writing scores by integrating datasets from UCL, Mendeley, and Kaggle. The goal is to create a robust predictive model using a Random Forest Regressor, optimized through cross-validation and hyperparameter tuning. After preprocessing the data (handling missing values, encoding categorical variables, and scaling numerical features), the project achieved a high predictive accuracy with an R² score of 0.84.

## Keywords
Student Performance Prediction, Random Forest, Data Mining, Machine Learning, Educational Analytics, Data Integration, Score Forecasting

## Introduction
Predicting academic outcomes helps educational institutions tailor interventions, develop better learning strategies, and assist underperforming students. This project focuses on predicting writing scores using a comprehensive dataset compiled from various educational platforms. It provides insights into the relationships between academic performance and factors like study habits, parental education, and internet access.

## Literature Review
Machine learning has gained significant attention for predicting student performance. Traditional statistical methods often fall short in modeling complex relationships. Studies utilizing datasets from UCI, Kaggle, and others show promising results using models like Decision Trees and Support Vector Machines. However, most models use isolated datasets. Our approach integrates multiple sources to enhance predictive accuracy.

## Need and Importance of the Study
Early identification of students at risk allows institutions to intervene in time, improving academic outcomes. This project highlights the value of integrating multiple data sources to enhance prediction accuracy and reliability, ultimately leading to better decision-making.

## Research Objectives
- Integrate datasets from UCL, Mendeley, and Kaggle for a comprehensive student profile
- Conduct extensive data preprocessing and feature engineering
- Develop a machine learning pipeline using Random Forest for score prediction
- Optimize model performance through hyperparameter tuning
- Analyze model results for actionable insights

## Research Methodology
- **Data Sources**: Student performance datasets from UCL, Mendeley, and Kaggle
- **Preprocessing**: Data merging, type conversion, missing value imputation, categorical encoding, and feature scaling
- **Modeling**: Random Forest Regressor with cross-validation and hyperparameter tuning
- **Evaluation**: R² Score, Mean Squared Error, k-fold Cross-Validation

## Project Description
The project involves creating a machine learning pipeline to predict student writing scores based on features like gender, study time, previous grades, and internet access. The system performs data preprocessing, trains a Random Forest model, and evaluates performance. The model is optimized through GridSearchCV for hyperparameters like the number of estimators and maximum depth.

### UML Diagrams
1. **Use Case Diagram**:
   - Actors: Admin, Educator
   - Use Cases: Import Data, View Results, Export Model, Predict Scores

2. **Activity Diagram**:
   - Sequence: Start → Upload Dataset → Preprocess → Train Model → Evaluate → Generate Report → End

3. **Class Diagram**:
   - Classes: DatasetManager, PreprocessingEngine, MLModel, Evaluator
   - Relationships: DatasetManager aggregates data; PreprocessingEngine cleans and encodes; MLModel trains and predicts

## Research Objective-wise Work Done
- **Dataset Integration**: Merged and cleaned data from UCL, Mendeley, and Kaggle
- **Feature Engineering**: Created new features and handled missing values
- **Model Construction and Training**: Developed a modular pipeline for preprocessing and training
- **Performance Evaluation**: Conducted 5-fold cross-validation and hyperparameter optimization

## Project Outcome
- Achieved high model accuracy with an R² score of 0.84
- Developed a scalable pipeline for continuous evaluation of student performance
- Identified key predictors, such as study time and internet access, influencing writing scores

## Project Limitations
- Limited dataset size may affect the generalizability of the model
- Many fields required imputation due to missing or inconsistent entries
- The current model doesn’t incorporate longitudinal or psychological data

## Potential Enhancements
- Expand dataset to include diverse students from different regions and institutions
- Incorporate temporal data to track performance over multiple terms
- Explore neural networks or deep learning for handling non-linear relationships
- Implement a real-time dashboard for institutional use

## Conclusion
The project demonstrates how machine learning can significantly improve educational assessment mechanisms. By integrating multiple datasets, a Random Forest model effectively predicts student writing scores. With further enhancements, this approach can be extended to a wider range of academic applications, supporting early interventions and personalized learning strategies.

---

For more information, check the project's repository or feel free to contribute!
