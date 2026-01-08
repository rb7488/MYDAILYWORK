# MYDAILYWORK
# Titanic Survival Prediction 🚢

## 📌 Project Overview

This project aims to build a machine learning model that predicts whether a passenger survived the Titanic disaster based on various features such as passenger class, gender, age, family size, fare, and port of embarkation.

This is a classic binary classification problem and is widely used as an introductory project in Data Science and Machine Learning.

---

## 📊 Dataset

* Source: Kaggle (Titanic Dataset)
* Total Records: 418 passengers
* Target Variable: `Survived`

  * `0` → Did not survive
  * `1` → Survived

### Key Features Used

* `Pclass` – Passenger class
* `Sex` – Gender
* `Age` – Age of passenger
* `SibSp` – Number of siblings/spouses onboard
* `Parch` – Number of parents/children onboard
* `Fare` – Ticket fare
* `Embarked` – Port of embarkation

---

## 🔍 Exploratory Data Analysis (EDA)

During EDA, the following insights were observed:

* Female passengers had a significantly higher survival rate than males.
* First-class passengers showed better survival chances compared to second and third class.
* Missing values were present in Age, Fare, and Cabin columns.
* The Cabin column had excessive missing values and was removed.

---

## 🧹 Data Preprocessing

* Dropped columns: `PassengerId`, `Name`, `Ticket`, `Cabin`
* Missing values handled:

  * `Age` filled using median
  * `Fare` filled using median
* Categorical variables encoded using Label Encoding:

  * `Sex`
  * `Embarked`

---

## 🤖 Model Building

* Model Used: **Logistic Regression**
* Train-Test Split: 80% training, 20% testing
* Evaluation Metrics:

  * Accuracy
  * Confusion Matrix
  * Precision, Recall, F1-score

---

## 📈 Model Performance

* Accuracy achieved: **100%**
* Confusion Matrix and Classification Report indicated perfect precision and recall on the test set.

⚠️ **Note:**
The high accuracy is influenced by strong feature correlations and dataset bias (particularly gender). Results should be interpreted cautiously for real-world generalization.

---

## 🧠 Key Learnings

* Importance of EDA before model building
* Handling missing data effectively
* Feature selection and encoding
* Understanding evaluation metrics beyond accuracy

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 📌 Conclusion

This project demonstrates a complete end-to-end machine learning workflow, from data understanding and preprocessing to model training and evaluation. It serves as a strong foundational project for beginners in Data Science.

---

📎 **Internship Task – MyDailyWork Data Science Internship**

