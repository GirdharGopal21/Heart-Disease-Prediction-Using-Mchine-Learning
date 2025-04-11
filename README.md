### 📌 **Title**
**Heart Disease Prediction System using Machine Learning**

---

### 🧠 **Abstract**
- Heart disease is common and treatment can be costly.
- The aim is to predict the disease early using ML and data mining.
- Early prediction improves treatment and reduces cost.
- The system uses ML techniques like Naive Bayes and Decision Trees.
- Predicts based on profile parameters: blood pressure, age, sex, cholesterol, blood sugar.
- Evaluation through confusion matrix, accuracy, precision, and recall.

---

### 📖 **Introduction**
- Healthcare collects vast data often unused.
- Heart Disease Prediction System (HDPS) uses 13 parameters.
- Uses ML algorithms: Naive Bayes, Decision Tree, and Multilayer Perceptron.
- Establishes patterns in medical data for predictions.

---

### 🎯 **Aim**
- Predict heart disease based on user input and database values.

---

### 🎯 **Objective**
- Develop a system that extracts hidden knowledge from historical heart disease data using data mining.

---

### 🌐 **Project Scope**
- Generic software for any organization.
- Summarizes large data efficiently for decision-making.

---

### 🧩 **Modules**
- **Patient Login/Registration**
- **My Details / Disease Prediction**
- **Search Doctor / Feedback**
- **Doctor Login / Patient Details**
- **Admin Login**
  - Add/View Doctor
  - Add/View Dataset
  - View Disease / View Patient
  - View Feedback
  - Notifications for predictions

---

### 💻 **Technology Stack**

#### 👨‍💻 Languages:
- HTML, CSS, JavaScript, Python

#### ⚙️ Frameworks:
- Bootstrap, Django

#### 🤖 Machine Learning Algorithms:
- Gradient Boosting
- Logistic Regression

#### 📦 Libraries:
- NumPy, Pandas, Scikit-learn

#### 🗃️ Database:
- SQLite

#### 🧠 Dataset:
- [heart.csv on GitHub](https://github.com/Kumar-laxmi/Heart-Disease-Prediction-System/blob/main/Machine_Learning/heart.csv)

#### 🛠️ IDEs:
- VS Code, PyCharm

#### 🖥️ Operating Systems:
- macOS, Ubuntu, Windows

---

### ▶️ **Run Locally**

```bash
git clone https://github.com/Kumar-laxmi/Heart-Disease-Prediction-System
cd Heart-Disease-Prediction-System
python manage.py runserver
```

---

### 🧠 **ML Model Training Snippet**

```python
def prdict_heart_disease(list_data):
    ...
    nn_model = GradientBoostingClassifier(...)
    nn_model.fit(X_train, y_train)
    pred = nn_model.predict([list_data])
    ...
```

---

### 📄 **Full Report**
- [Click Here for Project Report PDF](https://github.com/Kumar-laxmi/Heart-Disease-Prediction-System/blob/main/REPORT/PYTHON%20CAPSTONE%20PROJECT%20REPORT%20(TEAM%202).pdf)

---

### 📽️ **Demo Video**
- [Click Here for Demo](https://amritacampuschennai-my.sharepoint.com/:v:/g/personal/ch_en_u4cse20005_ch_students_amrita_edu/ESuaLdQqmNdFjzSBcMiTpaABWPQ2kZWEwCJ53HsY3UdHHg)

---

### 📸 **Output Screenshots**
- Welcome Page
- Admin Dashboard
- Heart Detail Form
- Search Logs
- View Details
- Help Video
- Doctor Records

---

### ⚠️ **Note**
- GitHub Pages is not working.

