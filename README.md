# CSC410 Project: Diabetes Prediction using Big Data

## Overview
This project was part of the CSC410 course, which focused on Big Data and Data Research. The goal of the project was to analyze patient data and implement a machine learning algorithm to predict whether a patient has diabetes. A value of `1` indicates the presence of diabetes, while `0` indicates the absence.

## Tools and Libraries
To achieve this, we utilized the following tools and libraries:

- **Python**: The primary programming language for the project.
- **Matplotlib**: For data visualization.
- **Pandas**: For data manipulation and creation of dataframes.
- **NumPy**: For numerical computations.
- **itertools**: For advanced iteration and combinatorics.
- **scikit-learn**: To implement the machine learning algorithm.

## Dataset
The dataset used for this project was a CSV file containing patient data with the following properties:

- **Pregnancies**: Number of times the patient has been pregnant.
- **Glucose**: Glucose concentration levels.
- **Blood Pressure**: Diastolic blood pressure levels (mm Hg).
- **Skin Thickness**: Triceps skinfold thickness (mm).
- **Insulin**: Serum insulin levels (mu U/ml).
- **BMI**: Body mass index (weight in kg/(height in m)^2).
- **Age**: Age of the patient.
- **Outcome**: Target variable (1 for diabetic, 0 for non-diabetic).

## Methodology

### 1. Data Preprocessing
- Loaded the data from the CSV file into a Pandas DataFrame.
- Performed data cleaning to handle missing or anomalous values.
- Explored the dataset using descriptive statistics and visualizations.

### 2. Data Visualization
Utilized Matplotlib to visualize relationships in the dataset, such as:
- Distribution of glucose levels among diabetic and non-diabetic patients.
- Correlation between BMI and diabetes.
- Age distribution for diabetic versus non-diabetic individuals.

### 3. Feature Engineering
- Selected relevant features from the dataset.
- Normalized numerical values to standardize the scale.
- Split the data into training and testing sets.

### 4. Machine Learning
- Implemented a machine learning model using scikit-learn.
- Trained the algorithm on the training data.
- Evaluated the model's accuracy on the testing data.

### 5. Prediction
- The algorithm predicts the outcome based on input patient data.
- Outputs `1` if the patient is diabetic and `0` otherwise.

## Results
The implemented algorithm achieved a dissatisfactory level of accuracy in predicting diabetes. Our conclusion was having a larger dataset . Visualizations revealed key patterns and trends in the dataset, such as the influence of glucose and BMI on diabetes likelihood.

## Conclusion
This project demonstrated the application of Big Data techniques and machine learning to address a real-world healthcare problem. By leveraging Python libraries like Pandas, NumPy, and scikit-learn, we successfully built a data-driven solution for diabetes prediction.

## Future Work
- Enhance the model by exploring advanced machine learning algorithms.
- Incorporate more data to improve prediction accuracy.
- Expand the dataset to include a more diverse population for better generalization.

Special thanks to the CSC410 course instructor Dr Ali for their input and guidance throughout the project.


