# Loan Default Data Prediction & Risk Analysis
The project focus on loan default prediction using machine learning to classify high-risk borrowers. It involves data preprocessing (pandas, NumPy), feature engineering, model selection (scikit-learn), and hyperparameter tuning (Optuna). Performance is evaluated using ROC-AUC, precision-recall, and F1 score, optimizing risk assessment strategies.

---

By leveraging **data preprocessing, feature engineering, exploratory data analysis (EDA), and machine learning**, this project uncovers patterns in borrower behavior and identifies risk factors affecting loan defaults. Key areas of analysis include **handling class imbalance, hyperparameter tuning (Optuna), and model evaluation using precision-recall and ROC-AUC metrics**.

The insights gained can be applied to **credit risk assessment, financial modeling, and strategic loan approvals**. Through **visualization and statistical modeling**, this project demonstrates practical data science techniques for real-world financial applications.

---

## Project Aim  
This project aims to **predict loan default risk** by analyzing borrower data and building a classification model to improve credit risk assessment and decision-making.

---

## Technical Skills Demonstrated  
- **Data Preprocessing & Cleaning**: Handling **missing values**, encoding categorical variables, and structuring datasets for analysis.  
- **Feature Engineering**: Creating **new features** to enhance predictive accuracy.  
- **Exploratory Data Analysis (EDA)**: Visualizing borrower trends, loan distributions, and correlations.  
- **Class Imbalance Handling**: Applying **under-sampling**, **SMOTE**, and **class weighting** to improve model fairness.  
- **Machine Learning Model Selection**: Evaluating **logistic regression, decision trees, random forests, and KNeighbors classifiers**.  
- **Hyperparameter Tuning**: Using **Optuna** for optimizing model parameters.  
- **Model Evaluation**: Assessing models with **ROC-AUC, precision-recall curves, and F1 score**.  

---

## Files in This Repository  
| File | Description |
|------|------------|
| `Loan Default Data Prediction & Risk Analysis.ipynb` | Jupyter Notebook containing data preprocessing, EDA, and model training. |
| `test_task.csv` | Loan dataset containing borrower details and loan performance indicators. |

---

## How to Run This Project  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/loan-default-prediction.git
2. **Navigate to the project directory**
   ```bash
   cd loan-default-prediction
3. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn optuna
4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
5. Open and run "Loan Default Data Prediction & Risk Analysis.ipynb"

---

## Business Scenario  
Financial institutions face challenges in **identifying high-risk borrowers** and **minimizing loan defaults**. This project addresses critical questions in **credit risk assessment**:

- **Which borrower features strongly indicate default risk?**  
- **How does class imbalance affect model predictions?**  
- **Which machine learning model performs best in predicting loan defaults?**  
- **What approval thresholds optimize default rates while maintaining loan volume?**  

---

## Methodology & Technical Skills Demonstrated  

### 1. Data Cleaning & Preprocessing  
- **Handled missing data** and standardized categorical features.  
- **Mapped binary variables** for model compatibility.  

### 2. Exploratory Data Analysis (EDA)  
- **Visualized default distribution** and feature correlations.  
- **Examined borrower demographics and loan characteristics.**  

### 3. Handling Class Imbalance  
- **Under-sampled the majority class** to improve model learning.  
- **Experimented with SMOTE for synthetic data generation.**  

### 4. Model Selection & Training  
- **Tested multiple classifiers**: Logistic Regression, Random Forest, KNeighbors.  
- **Optimized hyperparameters** using **Optuna**.  

### 5. Model Evaluation  
- **Assessed model performance** using **ROC-AUC, precision-recall curves, and F1 scores**.  
- **Plotted ROC and PR curves** for visual comparison.  

---

## Key Findings & Conclusion  
- **KNeighbors performed best**, achieving the highest F1 score for the minority class.  
- **Under-sampling improved predictive performance**, but required careful tuning.  
- **Hyperparameter tuning (Optuna) significantly enhanced model accuracy.**  
- **A well-calibrated approval threshold helps balance risk and loan volume.**  

---

## **Contact & Contributions**  
Feel free to explore and contribute! If you have any suggestions, reach out or submit a pull request.  

- **Email**: [jordan.c.l.wright@gmail.com](mailto:jordan.c.l.wright@gmail.com)  

---

### **Author:** Jordan  
[GitHub Profile](https://github.com/JordanConallLuthaisWright)
