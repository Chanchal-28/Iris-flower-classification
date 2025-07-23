# 🌸 Iris Flower Classification

A simple machine learning project using **Scikit-learn** to classify iris flower species (`Setosa`, `Versicolor`, `Virginica`) based on their **sepal** and **petal** measurements.

---

## 📁 Dataset

- The dataset used is **[Iris.csv](Iris.csv)** containing 150 samples with the following features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
  - Species (Target)

---

## 🎯 Objective

To train a machine learning model that can **predict the species** of an iris flower using its measurements.

---

## 📌 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (optional)

---

## 🧠 ML Model Workflow

1. Load dataset (`Iris.csv`)
2. Preprocess data
3. Split into training & testing sets
4. Train using machine learning models like:
   - Logistic Regression
   - Decision Tree Classifier
   - (Optional) KNN or SVM
5. Evaluate model performance
6. Predict iris species

---

## 📊 Sample Output 
  
    📊 Classification Report:
   

                 precision      recall    f1-score    support

    Iris-setosa       1.00      1.00      1.00        10
    Iris-versicolor   1.00      1.00      1.00         9
    Iris-virginica    1.00      1.00      1.00        11

       
    accuracy                              1.00        30  
    macro avg         1.00      1.00      1.00        30    
    weighted avg      1.00      1.00      1.00        30

    🌸 Sample Prediction:
  
      Input: [[5.1, 3.5, 1.4, 0.2]]
      Predicted Species: Iris-setosa

---

## ▶️ How to Run


1. Clone this repository:
   ---
   git clone https://github.com/Chanchal-28/iris-flower-classification.git

2. Navigate to the folder:
   --- 
   cd iris-flower-classification

3. Install dependencies:
   ---
   pip install pandas scikit-learn numpy matplotlib

4. Run the script:
   ---
   python iris_classifier.py

### ✅ Should you include it in your project?

**Yes, absolutely.** It's professional and helpful. You already have your code and data working — this section just tells others how to run it on their machine.
