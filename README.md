# Ignite-Intern-Predicting-Student-Performance-Project


### Introduction
This project aims to predict the final grades of students using various features such as demographics, study habits, and previous grades. The model uses data preprocessing, exploratory data analysis (EDA), and machine learning techniques to make accurate predictions.

### Dataset
The dataset used in this project is the "Student Performance Dataset" from the UCI Machine Learning Repository. It includes features like demographic information, study time, and previous grades.

### Project Structure
```
.
├── data
│   ├── student-mat.csv            # Dataset file
├── notebooks
│   ├── ignite_intern_student_performace_project.ipynb  # Jupyter notebook with the project code
├── images
│   ├── grade_distribution.png     # Distribution of final grades
│   ├── correlation_matrix.png     # Correlation matrix visualization
│   ├── actual_vs_predicted.png    # Actual vs Predicted grades visualization
│   ├── feature_importances.png    # Feature importances visualization
│   ├── residual_plot.png          # Residual plot visualization
├── README.md                      # README file
└── requirements.txt               # Dependencies
```


### Model Description
- **Preprocessing**: The data was cleaned and categorical variables were converted to numeric using one-hot encoding.
- **Model**: A Random Forest Regressor was trained to predict the final grades (G3).
- **Evaluation**: The model was evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score.

### Evaluation
- **Mean Squared Error**: 1.93
- **Mean Absolute Error**: 1.09
- **R2 Score**: 0.85







