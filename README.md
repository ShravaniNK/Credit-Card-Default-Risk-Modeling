# Credit-Card-Default-Risk-Modeling
 
- Dataset Characteristics: Multivariate
-  Subject Area - Business
- Associated Tasks - Classification
- Feature Type - Integer, Real
- Instances - 30000
- Features - 23

- Dataset Information: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

- Built and validated Probability of Default (PD) models using logistic regression on consumer credit card performance data.

- Fetaure Engineered behavioral risk features including delinquency trends, credit utilization, and payment ratios to improve model accuracy.

- Evaluated model performance for original unbalanced and SMOTE balanced data using ROC–AUC, KS statistic, confusion matrices, and score band analysis.



![Class Dsitribution](https://github.com/ShravaniNK/SQL-Gestational_Diabetes_DataAnalysis/blob/e517ca4b9c4d238b5cb75eab06e4ff51e7d8f6f4/GDM_ERD.jpg)

![SMOTE Balanced Data](https://github.com/ShravaniNK/SQL-Gestational_Diabetes_DataAnalysis/blob/e517ca4b9c4d238b5cb75eab06e4ff51e7d8f6f4/GDM_ERD.jpg)

![ROC curves](https://github.com/ShravaniNK/SQL-Gestational_Diabetes_DataAnalysis/blob/e517ca4b9c4d238b5cb75eab06e4ff51e7d8f6f4/GDM_ERD.jpg)

![Table Comparison](https://github.com/ShravaniNK/SQL-Gestational_Diabetes_DataAnalysis/blob/e517ca4b9c4d238b5cb75eab06e4ff51e7d8f6f4/GDM_ERD.jpg)

- Conclusions: Final Model Selection Insight

  - Original model:

    Better for portfolio-level reporting where false alarms are costly

    Poor for identifying high-risk borrowers

  - SMOTE model:

    Better for credit risk decision support, collections prioritization, and stress testing

    Aligns more closely with regulatory and business objectives focused on risk mitigation
