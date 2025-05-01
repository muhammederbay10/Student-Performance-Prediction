
# 🎓 Student Performance Prediction

This project predicts student performance based on various demographic, behavioral, and academic features. Using linear regression, the model estimates exam scores and provides insights into which factors most influence student outcomes.

---

## 📌 Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Features](#features)  
- [Modeling](#modeling)  
- [Evaluation](#evaluation)  
- [Visualizations](#visualizations)  
- [Contributing](#contributing)  
- [License](#license)  

---

## 📖 Overview

This project involves a complete machine learning pipeline:
- Loading and cleaning a student dataset
- Visualizing trends and correlations
- Encoding categorical data
- Building a linear regression model to predict exam scores
- Evaluating the model using standard metrics
- Analyzing which features have the most predictive power
- Providing recommendations based on results

---

## 📂 Dataset

The dataset is provided in the `final_student_data.csv` file and contains the following columns:

- `StudentID`: Unique student identifier  
- `Age`: Student age  
- `Gender`: Gender of the student  
- `Ethnicity`: Ethnic background  
- `ParentalEducation`: Parental education level  
- `StudyTimeWeekly`: Weekly study time (in hours)  
- `Absences`: Number of absences  
- `ParentalSupport`: Level of parental support  
- `Extracurricular`: Participation in extracurricular activities  
- `Sports`: Participation in sports  
- `Music`: Participation in music programs  
- `Volunteering`: Involvement in volunteer activities  
- `ExamScore`: **Target variable** — final exam score (0–100)  
- `Result`: Categorical label (`Pass` or `Fail`) based on score  

---

## ⚙️ Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/muhammederbay10/Student-Performance-Prediction.git
cd Student-Performance-Prediction
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Open the Jupyter notebook:

   ```bash
   jupyter notebook "Student Performance Prediction.ipynb"
   ```

2. Run all cells in order to:
   - Load and clean the data  
   - Visualize distributions and correlations  
   - Encode categorical features  
   - Train and evaluate the regression model  
   - Interpret results and feature importance  

---

## ✨ Features

### ✅ Data Preparation
- Handles missing values (dropped)
- Categorical encoding using `LabelEncoder` and `OneHotEncoder`

### 📊 Data Visualization
- Histogram of exam scores
- Boxplot by parental education
- Correlation heatmap

### 🤖 Machine Learning
- Linear Regression model (scikit-learn)
- Train-test split
- Predictions on test set

### 🔍 Feature Analysis
- Feature importance via model coefficients
- Highlights which student characteristics most influence exam scores

---

## 🧠 Modeling

The project uses **`LinearRegression`** from `scikit-learn` with these steps:
- Encode categorical features appropriately
- Separate target variable (`ExamScore`) from features
- Train-test split
- Model training on the training set
- Prediction and performance analysis

---

## 📈 Evaluation

Model performance is measured using:

- **R² Score** – Proportion of variance explained  
- **Mean Squared Error (MSE)** – Average squared prediction error  

---

## 📊 Visualizations

Included plots:
- **Histogram** of `ExamScore` distribution  
- **Boxplot** of scores by `ParentalEducation`  
- **Heatmap** of feature correlations  
- **Bar chart** for feature importance from linear regression coefficients  

---

## 🙌 Contributing

Contributions are welcome!  
To contribute:
1. Fork the repository  
2. Create a new branch  
3. Make your changes  
4. Submit a pull request  

---



This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

---

Let me know if you want me to help create a `requirements.txt` file or a contribution guideline.
