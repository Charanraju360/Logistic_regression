# Logistic Regression on Iris Dataset 🌸

## 📌 Project Overview
This project demonstrates **Logistic Regression** using the **Iris dataset**.  
The Iris dataset is one of the most popular datasets in machine learning, containing 150 samples of iris flowers with four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width  

The goal is to classify the flowers into three species:
- Setosa
- Versicolor
- Virginica  

---

## 📂 Files in this Project
- `iris.csv` → Dataset containing flower measurements.  
- `logistic_regression.ipynb` → Jupyter Notebook with data preprocessing, visualization, model training, and evaluation.  

---

## ⚙️ Steps Performed
1. **Data Loading & Exploration**
   - Loaded the Iris dataset from CSV.
   - Checked Null values either present or not.

2. **Data Visualization (Matplotlib)**
   - Scatter plots (Petal length vs Petal width, Sepal length vs Sepal width).

3. **Preprocessing**
   - Split dataset into training and testing sets.
   - verified the sizes of the train and test split.

4. **Model Training**
   - Applied **Logistic Regression** from `sklearn`.
   - Trained the model on training data.

5. **Evaluation**
   - Calculated accuracy score on test data.

---

## 📊 Results
- Logistic Regression achieved good accuracy in classifying the Iris species.  
- Features **Petal Length** and **Petal Width** are the most useful for classification.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/iris-logistic-regression.git
   ````

2. Navigate into the project folder:

   ```bash
   cd iris-logistic-regression
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Run Jupyter Notebook:

   ```bash
   jupyter notebook logistic_regression.ipynb
   ```

---

## 📦 Requirements

* Python 3.x
* pandas
* matplotlib
* scikit-learn
* jupyter

Install them with:

```bash
pip install pandas matplotlib scikit-learn jupyter
```
