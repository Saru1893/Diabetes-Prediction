# 🩺 Diabetes Prediction using Machine Learning

A machine learning project that predicts whether a person is diabetic based on diagnostic medical measurements. The model is trained using the Pima Indians Diabetes Dataset and implemented in Python using Scikit-learn.

---

## 📌 Project Overview

Early detection of diabetes is important for timely treatment and better health outcomes. This project builds a classification model that predicts whether a patient has diabetes based on several health-related features.

The workflow includes:
- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling
- Model training using Support Vector Machine (SVM)
- Model evaluation
- Prediction on new patient data

---

## 📂 Dataset

**Dataset:** Pima Indians Diabetes Dataset

### Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target

- **0** → Non-Diabetic
- **1** → Diabetic

---

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn

---

## 📚 Machine Learning Workflow

1. Import libraries
2. Load the dataset
3. Explore and analyze the data
4. Separate features and target
5. Split data into training and testing sets
6. Standardize features using `StandardScaler`
7. Train the model using Support Vector Machine (SVM)
8. Evaluate model performance
9. Predict diabetes for new patient data

---

## 🤖 Model Used

**Support Vector Machine (SVM)**

SVM is a supervised machine learning algorithm used for classification tasks. It identifies the optimal decision boundary that best separates diabetic and non-diabetic patients.

---

## 📊 Model Evaluation

The model is evaluated using:

- Training Accuracy
- Testing Accuracy

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Diabetes-Prediction.git
```

2. Navigate to the project folder

```bash
cd Diabetes-Prediction
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook or open the notebook in Google Colab.

---

## 📁 Project Structure

```
Diabetes-Prediction/
│
├── Diabetes_Prediction.ipynb
├── diabetes.csv
├── requirements.txt
├── README.md
└── LICENSE (optional)
```

---

## 📸 Project Output

The trained model predicts:

- **0 → Non-Diabetic**
- **1 → Diabetic**

Example:

```
Input:
(6,148,72,35,0,33.6,0.627,50)

Prediction:
The person is diabetic.
```

---

## 🎯 Future Improvements

- Perform more detailed Exploratory Data Analysis (EDA)
- Compare multiple machine learning algorithms
- Hyperparameter tuning
- Deploy the model using Streamlit or Flask
- Improve evaluation using Precision, Recall, F1-score, and ROC-AUC

---

## 👨‍💻 Author

**Saru**

Computer Science & Engineering Student

Interested in Machine Learning, Data Structures & Algorithms, and Software Development.

---

⭐ If you found this project useful, consider giving the repository a star!
