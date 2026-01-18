# Bank Marketing Campaign Analysis

**Objective:** Predict term deposit subscriptions and provide actionable marketing insights using Python.

---

## Dataset
- Source: Bank Marketing dataset (originally from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing), accessed via Kaggle)
- Description: Contains data on bank clients, previous campaigns, and campaign outcomes.
- Target variable: `deposit` (1 = subscribed to term deposit, 0 = did not subscribe)

---

## Tools & Libraries
- Python
- Pandas & NumPy
- Seaborn & Matplotlib (for visualization)
- Plotly (interactive visualizations)
- Scikit-learn (machine learning models)
- Google Colab (for cloud-based execution)

---

## Workflow
1. **Data Cleaning & Preprocessing**  
   - Handled missing values and categorical encoding
   - Dropped or transformed irrelevant columns (like `duration` for realistic modeling)
2. **Exploratory Data Analysis (EDA)**  
   - Analyzed trends by age, job, month, campaign calls, and previous outcomes
   - Visualized subscription patterns using histograms, boxplots, and bar charts
3. **Feature Engineering**  
   - One-hot encoding for categorical variables
   - Derived useful features for model training
4. **Modeling**  
   - Stratified sampling for train-test split
   - Trained Logistic Regression and Decision Tree classifiers
5. **Evaluation & Insights**  
   - Confusion Matrix, ROC-AUC, Precision-Recall curves
   - Identified key features affecting term deposit subscription
6. **Business Recommendations**  
   - Target high-balance, middle-aged clients during peak months
   - Optimize marketing campaigns for better subscription rates

---

## Key Insights
- Middle-aged clients (30–55) are more likely to subscribe to term deposits.
- May shows the highest subscription rates.
- Job types like management and blue-collar have the most potential subscribers.
- Number of campaign calls has diminishing returns; more calls do not always increase subscription.

---

## How to Run in Colab
1. Open Google Colab: https://colab.research.google.com/drive/1D-OIjUNleusgZr0piEqMVs5u58Cz0uF2?usp=sharing
2. Upload `bank.csv` if needed, or access it from Google Drive/Kaggle.  
3. Run the notebook cells to reproduce analysis and visualizations.  
4. All plots and results are interactive and visible in Colab.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

**Author:** MURARI JOY PRANEETH 
**GitHub:**(https://github.com/)
