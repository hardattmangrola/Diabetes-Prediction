# Diabetes Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting diabetes using various machine learning models. The dataset used is the **Pima Indians Diabetes Dataset**, which contains health-related parameters such as glucose levels, blood pressure, BMI, insulin levels, and more.

We implemented and compared multiple classification models to determine the most accurate prediction approach.

## 📊 Dataset
- **Source:** Kaggle - Pima Indians Diabetes Dataset
- **Features:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- **Target:** Outcome (0 = Non-Diabetic, 1 = Diabetic)

## 🚀 Models Implemented
We applied the following machine learning models and evaluated their accuracy:

| **Model**          | **Accuracy** |
|--------------------|-------------|
| **K-Nearest Neighbors (KNN)** | 0.7800 |
| **XGBoost**       | 0.7850 |
| **Support Vector Machine (SVM)** | 0.7900 |
| **Random Forest** | **0.8000** (Best Performance) |

### 🔍 Observations:
- **Random Forest** provided the highest accuracy (80%).
- **SVM and XGBoost** performed well but slightly below Random Forest.
- **KNN had the lowest accuracy**, as it is sensitive to feature scaling and high-dimensional data.

## 📌 Future Improvements
To further optimize performance, we plan to:
- **Hyperparameter tuning** to refine model performance.
- **Feature engineering** to enhance predictive power.
- **Ensemble Learning** (Random Forest + XGBoost) to achieve higher accuracy (expected 82-85%).

## 💻 Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model training and evaluation script:
   ```bash
   python diabetes_prediction.py
   ```

## 📜 License
This project is open-source and available under the MIT License.

---
### 🔗 Connect with Me
💬 Feel free to reach out if you have suggestions or improvements!
📧 Email: hardattmangrola55@gmail.com
GitHub: [hardatt](https://github.com/hardattmangrola)

