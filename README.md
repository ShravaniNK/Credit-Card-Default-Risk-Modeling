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



![Class Dsitribution](https://github.com/ShravaniNK/Credit-Card-Default-Risk-Modeling/blob/e54e34ff69ef53685648455070866ba378285e8c/image1.PNG)

![SMOTE Balanced Data](https://github.com/ShravaniNK/Credit-Card-Default-Risk-Modeling/blob/55d2416256331fdbdf168d8fe927afaa2ecc6dda/image2.PNG)

![ROC curves](https://github.com/ShravaniNK/Credit-Card-Default-Risk-Modeling/blob/641314727094a26a6ada5e53fbb56145d59a559d/image3.PNG)

![Table Comparison](https://github.com/ShravaniNK/Credit-Card-Default-Risk-Modeling/blob/7742f535b3556fd84094a0cd3d8a3b58e8b20d04/image4.PNG)

- Conclusions: Final Model Selection Insight

  - Original model:

    Better for portfolio-level reporting where false alarms are costly

    Poor for identifying high-risk borrowers

  - SMOTE model:

    Better for credit risk decision support, collections prioritization, and stress testing

    Aligns more closely with regulatory and business objectives focused on risk mitigation
