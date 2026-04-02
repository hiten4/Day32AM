# Loan Approval System using Decision Tree & Random Forest

---

##  Project Structure

- **Part A** – Model building using Decision Tree and Random Forest  
- **Part B** – Extra Trees vs Random Forest comparison  
- **Part C** – Interview preparation (concepts + coding)  
- **Part D** – AI-assisted visualization and evaluation  

---

##  Dataset

A synthetic dataset of 2000 records was created with the following features:

- annual_income  
- credit_score  
- loan_amount  
- employment_years  
- debt_to_income  
- num_credit_cards  

**Target Variable:**  
- approved (1 = Approved, 0 = Rejected)

---

##  Workflow

1. Data Generation (synthetic dataset)  
2. Train-Test Split (80/20)  
3. Model Training:
   - Decision Tree (max_depth=4)
   - Random Forest (tuned using RandomizedSearchCV)  
4. Model Evaluation using:
   - Accuracy  
   - F1 Score  
   - ROC-AUC  
5. Feature Importance Analysis:
   - Default feature importance  
   - Permutation importance  

---

##  Decision Tree (Interpretability)

- Provides clear decision rules  
- Easy to explain to stakeholders  
- Suitable for regulatory environments  

---

##  Random Forest (Performance)

- Reduces overfitting using ensemble learning  
- Better generalization performance  
- Higher accuracy compared to Decision Tree  

---

##  Extra Trees vs Random Forest

| Feature            | Random Forest               | Extra Trees                  |
|------------------|---------------------------|-----------------------------|
| Split Selection   | Best split                | Random split                |
| Speed             | Slower                    | Faster                      |
| Variance          | Low                       | Lower                       |
| Accuracy          | Slightly higher           | Comparable                  |

---

##  Results

- Random Forest achieved better performance across metrics  
- Decision Tree provided strong interpretability  
- Trade-off between explainability and accuracy observed  

---

##  Key Learnings

- Bias-variance tradeoff in tree-based models  
- Importance of ensemble methods  
- Feature importance interpretation  
- Model evaluation beyond accuracy  

---

##  AI-Augmented Insights

A visualization was created to compare:

- Decision Tree  
- Random Forest  
- Logistic Regression  

### Key Observations:
- Decision Tree → High interpretability  
- Random Forest → High accuracy  
- Logistic Regression → Simpler, linear model  

### Limitations:
- AI output was slightly oversimplified  
- Did not include variance, assumptions, or detailed metrics  

### Improvements:
- Added better explanation of tradeoffs  
- Included additional evaluation aspects  

---

##  Tools & Libraries

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

##  How to Run

1. Open notebook in Google Colab  
2. Run all cells sequentially  
3. Review outputs and model performance  

---

#  Author

**Hiten Mistry**
