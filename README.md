# Diabetes Prediction Using Machine Learning 🏥

## Watch the Demo 📺

[![YouTube Video](https://img.shields.io/badge/YouTube-Watch%20Demo-red?logo=youtube&logoColor=white&style=for-the-badge)](https://youtu.be/l2WEjcAe3Hc)

![Image](https://github.com/user-attachments/assets/b6c30039-e65a-42a4-86a9-1163f3868b39)

## Overview 📖
This project predicts **diabetes risk** using the **Pima Indians Diabetes Dataset** with **machine learning**. The goal is to classify individuals as diabetic or non-diabetic based on health parameters like glucose level, BMI, and age. 

https://pima-indians-diabetes-prediction-project.streamlit.app/

## Dataset 📂
- **Name**: Pima Indians Diabetes Dataset
- **Source**: [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- **Features**:
  - Number of pregnancies
  - Glucose level
  - Blood pressure
  - Skin thickness
  - Insulin level
  - BMI
  - Diabetes pedigree function
  - Age
  - Outcome (0 = No Diabetes, 1 = Diabetes)

## Machine Learning Models 🧠
The project uses **two machine learning models**:
- **Random Forest Classifier** 🌳
- **Logistic Regression** 📈

## Web App Interface 💻
The project includes a **Streamlit web app** that allows users to input health parameters and get real-time diabetes predictions.

![Image](https://github.com/user-attachments/assets/8fcf0e9e-3d0d-4cea-8fc6-97c7aa356e2f)

## Files in the Repository 📁
- `Pima Indians Diabetes.ipynb` - Jupyter Notebook with data analysis and model training
- `app.py` - Streamlit web application for user interaction
- `model.pkl` - Saved machine learning model for predictions
- `scaling.pkl` - Preprocessing scaler for input normalization
- `requirements.txt` - List of dependencies

## How to Run 🏃‍♂️
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Diabetes-Prediction-Project.git
   cd Diabetes-Prediction-Project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Dependencies 📦
- Scikit-learn
- Streamlit
- Pandas
- NumPy
- Matplotlib

## Future Improvements 🔮
- Improve model accuracy by training on more data
- Add more machine learning models for comparison
- Deploy as a web service using Flask or FastAPI

## Author ✍️
- **DataScientist00**
- Kaggle: [Profile](https://www.kaggle.com/codingloading)

---
**⭐ If you found this project helpful, give it a star! ⭐**
