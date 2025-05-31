## 🎓 Student Performance Prediction using Logistic Regression

### 📌 Objective

To build a basic machine learning model that predicts whether a student will **pass or fail** based on:

* **Hours Studied**
* **Attendance (%)**

This project uses **Logistic Regression** for binary classification (1 = Pass, 0 = Fail).

---

### 📁 Dataset

A small manually created dataset with the following structure:

| Hours\_Studied | Attendance (%) | Pass/Fail |
| -------------- | -------------- | --------- |
| 5              | 85             | 1         |
| 2              | 60             | 0         |
| 4              | 75             | 1         |
| 1              | 50             | 0         |
| 3              | 70             | 1         |
| 6              | 90             | 1         |
| 2.5            | 65             | 0         |
| 3.5            | 80             | 1         |

---

### 🛠️ Tools & Technologies Used

* **Python**
* **Jupyter Notebook** / **Google Colab**
* **Libraries**:

  * `pandas`
  * `matplotlib`
  * `sklearn` (scikit-learn)

---

### 🚀 Steps Performed

1. **Dataset Creation** (manually in code)
2. **Data Visualization** using Matplotlib
3. **Model Training** using Logistic Regression
4. **Train-Test Split** using `train_test_split()`
5. **Prediction & Accuracy Calculation**
6. **Testing with New Input Values**

---

### 📈 Model Prediction Example

```python
new_data = pd.DataFrame({
    'Hours_Studied': [3, 1, 4.5],
    'Attendance': [80, 55, 78]
})
model.predict(new_data)
```

---

### ✅ Output

* **Accuracy Score** on test data printed in the notebook.
* **Predicted Results** for new input data.
