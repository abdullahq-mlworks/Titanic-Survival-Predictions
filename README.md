Titanic Survival Predictions using Logistic Regression🚢

This project predicts **Titanic passenger survival** using **Logistic Regression**.  
We preprocess the dataset (handle missing values, encode categorical features) and evaluate the model using **accuracy, confusion matrix, and classification report**.

---
📂 Project Structure

Titanic-Survival-Predictions/
│── Titanic Predictions.ipynb   # Main Jupyter Notebook
│── requirements.txt            # Required Python libraries
│── README.md                   # Project documentation

---

🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/abdullahq-mlworks/Titanic-Survival-Predictions.git
   cd Titanic-Survival-Predictions
````
2. Install dependencies:
   pip install -r requirements.txt

3. Open Jupyter Notebook:
   jupyter notebook "Titanic Predictions.ipynb"
---

📊 Features

* Preprocessing Titanic dataset (fill missing values, encode categorical columns)
* Train-test split (80/20)
* Logistic Regression model for binary classification
* Model evaluation:

  * **Accuracy Score**
  * **Confusion Matrix**
  * **Classification Report** (Precision, Recall, F1-score)

---
📷 Output Example

* **Accuracy** ≈ 0.78
* **Confusion Matrix** example:
  [[92 13]
   [21 53]]
  ```
* **Classification Report** with Precision, Recall, F1-score

---
🛠️ Libraries Used

* **scikit-learn** – ML model & evaluation metrics
* **seaborn** – Titanic dataset loader
* **numpy** – Data handling
* **matplotlib** – Visualization (optional)

---

📌 Notes

* Features used: `pclass, sex, age, sibsp, parch, fare`
* Target variable: `survived` (0 = No, 1 = Yes)
* Logistic Regression is chosen since the problem is **binary classification**.