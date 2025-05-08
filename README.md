# 🩺 Diabetic Disease Predictor

This is a Machine Learning project that predicts whether a person is likely to have diabetes based on various medical parameters. The model is trained using the Pima Indians Diabetes dataset and uses Support Vector Machine (SVM) for classification.

## 🚀 Features

- Data preprocessing and scaling
- Train-test split for model evaluation
- SVM-based classification
- Accuracy evaluation using sklearn metrics

## 🛠️ Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Scikit-learn (`sklearn`)

## 📦 Dependencies

Make sure you have the following dependencies installed:

```bash
pip install numpy pandas scikit-learn



## **📁 Dataset**

The model is trained on the Pima Indians Diabetes dataset, which includes features such as:

Number of Pregnancies

Glucose Level

Blood Pressure

Skin Thickness

Insulin Level

BMI

Diabetes Pedigree Function

Age


##**🧠 Machine Learning Workflow**

Data Loading: Load the dataset using Pandas.

**Preprocessing:**

Handle missing or zero values if necessary.

Standardize the dataset using StandardScaler.

**Model Training:**

Split data into training and testing sets using train_test_split.

Train an SVM model on the training data.

**Model Evaluation:**

Predict on test data.

Evaluate using accuracy_score.


##**📈 Results**

The SVM model provides a good baseline performance. You can experiment with other models like Random Forest or Logistic Regression for comparison.


##**📌 Future Improvements**

Add hyperparameter tuning using GridSearchCV

Implement cross-validation for better model validation

Create a frontend interface using Streamlit or Flask for user interaction


**Feel free to fork, improve, and customize this project!**


##**📃 License**

This project is licensed under the MIT License
