

## 🔍 SONAR Rock vs Mine Prediction using Logistic Regression

This project uses a Logistic Regression model to classify sonar signal returns as either a **rock** or a **mine**. It is a binary classification problem where sonar data is used to determine the type of object detected under the sea.

---

### 📂 Dataset

- **Source**: UCI Machine Learning Repository – [Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+%28Sonar,+Mines+vs.+Rocks%29)
- **Format**: CSV file with 61 columns:
  - 60 numeric features representing sonar signal energies.
  - 1 target column:
    - `R`: Rock
    - `M`: Mine

---

### 🛠️ Libraries Used

- `numpy`
- `pandas`
- `scikit-learn`

---

### 📊 Workflow

1. **Data Loading & Exploration**  
   Load and understand the structure of the dataset.

2. **Preprocessing**  
   - Splitting features (X) and labels (Y).
   - Train-test split.

3. **Model Training**  
   - Logistic Regression is used for binary classification.

4. **Evaluation**  
   - Accuracy score is used as the primary evaluation metric.

5. **Prediction System**  
   - User input-based prediction using the trained model.

---

### 🧠 Model

- **Algorithm**: Logistic Regression
- **Performance**: Accuracy-based evaluation (results vary slightly depending on train-test split).

---

### 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Thesushmit/Smart-Attendance-Management
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook project.ipynb
   ```

---

### 📌 Note

- Make sure the dataset file `Copy of sonar data.csv` is present in the same directory as the notebook.
- You can modify the input at the end of the notebook to test custom sonar readings.

---



### 🧑‍💻 Author

**Sushmit Partakke**  
2nd Year, Symbiosis Nagpur  
Python • ML • Web Dev  



