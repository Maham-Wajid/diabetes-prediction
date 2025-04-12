# 🩺 Diabetes Prediction Using Logistic Regression

This project uses a logistic regression model to predict whether a person is diabetic based on medical features like glucose level, blood pressure, insulin level, etc. The dataset is preprocessed, explored through visualizations, and used to train and test a predictive model.

---

## 📌 Overall Explanation

This project walks through the full machine learning pipeline:

1. **Data Import & Exploration**:
   - Load the `diabetes.csv` dataset using `pandas`.
   - Explore and summarize the data using `.head()` and `.describe()` methods.

2. **Visualization**:
   - Use `seaborn` and `matplotlib` to plot:
     - Outcome distributions
     - Scatter plots between outcome and age
     - Distributions of features like Age and Blood Pressure

3. **Data Preprocessing**:
   - Split the dataset into features (X) and target label (Y).
   - Use `train_test_split()` from `sklearn` to create training and testing sets.

4. **Model Training**:
   - Apply logistic regression using `LogisticRegression()` from `sklearn.linear_model`.
   - Fit the model on the training data.

5. **Model Evaluation**:
   - Predict on test data.
   - Evaluate using `classification_report` and `confusion_matrix`.

6. **Prediction for a New Patient**:
   - Provide a custom input of 8 features to test the model's prediction.

---

## 🌟 STAR Format Summary

### ✅ **S - Situation**
Diabetes is a life-threatening chronic illness. Early detection can significantly improve quality of life. We have patient medical data available for analysis.

### ✅ **T - Task**
Develop a predictive model that can classify whether a patient has diabetes based on their medical data.

### ✅ **A - Action**
- Load and explore the data
- Visualize relationships in the data
- Train a logistic regression model
- Evaluate its performance
- Use the model to predict on new patient data

### ✅ **R - Result**
Achieved a working machine learning model capable of making predictions on unseen data with measurable performance.

---

## 🚀 How to Run the Project

### ▶️ Run on Google Colab (Recommended for Beginners)
1. Open this link:  
   [Colab Notebook](https://colab.research.google.com/drive/1azaOUtr8d0yHoksN5KscU-jjLMLmyifK)

2. Upload the `diabetes.csv` file to the session.

3. Run each cell step-by-step.

---

### 💻 Run Locally (For Developers)

#### 1️⃣ Clone the Project

```bash
git clone <repo-url>
cd diabetes-prediction
```

---

#### 2️⃣ Set Up Virtual Environment

python -m venv venv

# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate

---

#### 3️⃣ Install Dependencies

pip install -r requirements.txt

---

#### 4️⃣ Launch Jupyter Notebook

jupyter notebook

---

### 📁 Project Structure

diabetes-prediction/
├── diabetes.ipynb        # Jupyter Notebook with all steps
├── data
    └── diabetes.csv      # Dataset used
├── requirements.txt      # Required Python packages
└── README.md             # Project documentation

### 🧰 Technologies Used
Python
pandas
numpy
matplotlib
seaborn
scikit-learn
Jupyter Notebook
Google Colab

### Contributing 🤝
Contributions are welcome! Feel free to submit a Pull Request or open an Issue to improve this project.

### License 📄
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

### Contact 📧
For any queries, feel free to reach out 😊:

GitHub: Maham-Wajid
Email: ping.maham@gmail.com