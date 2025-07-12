# Heart Disease Prediction

This project is a machine learning-based heart disease prediction system built using Python and popular data science libraries such as **Pandas**, **Scikit-learn**, and **Matplotlib**. The aim is to predict whether a person has heart disease based on medical attributes.

## 🧠 Problem Statement

Heart disease is one of the leading causes of death globally. Early detection through data analysis can improve outcomes. This project leverages logistic regression to predict the presence of heart disease using patient data.


## 📁 Dataset

The dataset used in this project contains the following key features:

- `age`: Age of the patient
- `sex`: Gender (1 = male; 0 = female)
- `cp`: Chest pain type (0–3)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting ECG results (0–2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect)
- `target`: Diagnosis of heart disease (1 = yes; 0 = no)

---

## ⚙️ Technologies Used

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for modeling and evaluation)

---

## 📊 Model Used

- **Logistic Regression**
  - Data preprocessing (null handling, scaling)
  - Train-test split
  - Model training and prediction
  - Accuracy score evaluation

---

## 📈 Results

- **Accuracy Score**: Achieved model accuracy varies depending on the data preprocessing and train-test split.
- Confusion matrix and classification report used for evaluation.

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
