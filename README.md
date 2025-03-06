# Iris Flower Classification - Machine Learning Project

This project applies **Supervised Machine Learning algorithms** to classify iris flowers into three species: **Setosa**, **Versicolor**, and **Virginica**. The dataset is sourced from the **Seaborn library's iris dataset**, and multiple classification algorithms are compared to determine the best-performing model.
---
## 📊 Dataset
- **Source:** Seaborn Dataset Repository
- **Link:** [https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv)
- **Features:** 
    - Sepal Length
    - Sepal Width
    - Petal Length
    - Petal Width
- **Target:** 
    - Species (Setosa, Versicolor, Virginica)

---

## 🛠️ Algorithms Used
This project evaluates the performance of four different classification algorithms:

1. **Support Vector Machine (SVM)**
2. **Logistic Regression**
3. **Decision Tree Classifier**
4. **Random Forest Classifier**

---

## 🔬 Project Workflow

### 1️⃣ Data Loading
The dataset is loaded directly from the Seaborn GitHub repository using `pandas`.

### 2️⃣ Data Visualization
- Pairplots using `Seaborn` to explore relationships between features.
- Basic statistical description of the data using `pandas`.

### 3️⃣ Data Preprocessing
- Separating features and target.
- Splitting the data into training and testing sets (80% train, 20% test).

### 4️⃣ Model Training & Evaluation
- Each algorithm is trained using the training set.
- Predictions are made on the test set.
- Model accuracy is calculated using `accuracy_score`.
- Classification report is generated for detailed performance analysis.

### 5️⃣ Predictions on New Data
- A sample set of feature vectors is passed to the **SVM model** for species prediction.

---

## 📊 Model Performance (Sample)
| Algorithm                  | Accuracy (%) |
|-------------------|----------------|
| Support Vector Machine (SVM) | ~100% |
| Logistic Regression          | ~100% |
| Decision Tree Classifier     | ~100% |
| Random Forest Classifier     | ~100% |

> Accuracy may slightly vary depending on train-test split.

---
