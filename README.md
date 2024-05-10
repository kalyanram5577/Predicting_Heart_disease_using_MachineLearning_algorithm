# Predicting Heart Disease Using Machine Learning
# Overview
This repository contains code for predicting heart disease using a decision tree algorithm. Heart disease prediction is crucial for monitoring cardiovascular health, and machine learning techniques offer promising avenues for accurate prediction. In this project, we utilize a decision tree algorithm to predict the likelihood of heart disease based on a set of input features.

# Requirements
Python 3.x
Scikit-learn
Pandas
NumPy
Installation
Clone the repository:

# bash
# Copy code
git clone https://github.com/yourusername/heart_disease_prediction-using-decision-tree.git
cd heart_disease_prediction-using-decision-tree
# Dataset
The dataset used for this project contains a collection of samples with various features such as age, gender, blood pressure, cholesterol levels, etc., along with corresponding labels indicating the presence or absence of heart disease. The dataset is not included in this repository due to size constraints but can be easily integrated by placing it in the data directory with the appropriate file name.
# columns 
age: Age of the individual (in years)
sex: Gender of the individual (0 = female, 1 = male)
cp: Chest pain type (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic)
trestbps: Resting blood pressure (in mm Hg)
chol: Serum cholesterol level (in mg/dl)
fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
restecg: Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy)
thalach: Maximum heart rate achieved (in beats per minute)
exang: Exercise induced angina (1 = yes, 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping)
ca: Number of major vessels colored by fluoroscopy (0-3)
thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversable defect)
target: Presence of heart disease (1 = yes, 0 = no)

# Usage
Place your dataset file (in CSV format) containing the necessary features and heart disease labels in the data directory.
Modify the config.py file to specify the file name and column names corresponding to features and the target variable (heart disease).
Run the heart_disease.py script:
# bash
# Copy code
python heart_disease.py
The script will train the decision tree model on the provided dataset and display evaluation metrics such as accuracy, precision, recall, and F1-score. Additionally, the trained model will be saved as a serialized file (heart_disease_prediction_model.pkl) for future use.

# Model Evaluation
The decision tree model's performance is evaluated using various metrics to assess its predictive accuracy and generalization capabilities. These metrics include accuracy, precision, recall, and F1-score, providing insights into the model's ability to correctly predict heart disease based on the input features.

# License
This project is licensed under the APACHE 2.0 License - see the LICENSE file for details.

#Contributors
Kalyan Ram
Sai Kiran
Feedback and Contributions
Feedback, bug reports, and contributions are welcome! Feel free to open an issue or submit a pull request.

#Questions or Support
If you have any questions or need support regarding the project, feel free to contact Your Name.

#References
[1] Scikit-learn: Machine Learning in Python. Scikit-learn Documentation
[2] Pandas: Powerful data structures for data analysis. Pandas Documentation
[3] NumPy: The fundamental package for scientific computing with Python. NumPy Documentation
