# BMIN503/EPID600 Final Project
**About my project:**

**Project Title**

Machine Learning Based Survival Prediction in Non-metastatic Triple Negative Breast Cancer Using SEER Database

**Author Information**

Name: Wenyuan(Vivian) Ye; 
Institution: School of Medicine, University of Pennsylvania; 
Email: YeWen@pennmedicine.upenn.edu

**Objective**

Breast cancer(BC) is the second most commonly diagnosed cancer in women in the United States, and the primary cause of death among women worldwide. The ability to estimate prognosis is crucial for both patients and providers in order to select the most appropriate treatment. However, few researches using machine learning to study TNBC prognosis have been conducted. This project aimed to analyze the prognostic factors of patients with non-metastatic triple negative breast cancer (TNBC) and to construct and compare prediction models for forecasting the 3-, and 5-year survival based on machine learning.

**Methodology**

A total of 5058 female patients with non-metastatic TNBC were extracted from the Surveillance, Epidemiology, and End Results (SEER) database and patient demographics and clinical characteristics were gathered. Univariate and multivariate Cox regression analysis were used to identify the independent risk variables for overall survival of patients. These selected variables were then estimated through the Kaplan–Meier (KM) curves using the log rank test. Four models, including Logistic Regression(LR), Decision Tree(DF), Random Forest(RF), and Gradient Boosting Machine(GBM), for predicting the 3-, and 5-year survival were constructed by using 10-fold cross-validations, validated and compared by performing receiver operating characteristics (ROC) curves with area under the receiver operating characteristic curves (AUC).

**Results**

Seven variables, including age, race, radiation, chemotherapy, surgery, AJCC T stage and AJCC N stage, were identified as the independent prognostic factors of patients with non-metastatic TNBC during follow-up. AJCC T and N features derived from AJCC staging turned to be the most important factors in the four models, showing the greatest impact in predicting 3- and 5-year survival. GBM exhibited the best performance over the other three models, supported by an internal validation cohort with AUC of 0.809 and 0.788 for 3- and 5-year survival, respectively.

**Conclusion**

The findings of this study suggested that the GBM model was a trustful and efficacious model to predict the survival outcomes of TNBC patients. It has the potential to help clinicians better distinguish TNBC patients with high risk and devise better-individualized management plans. However, the models created in this study have yet to be confirmed in the external validation cohort.

**Keywords**

Triple negative breast cancer, Overall survival, SEER database, Machine learning, Gradient Boosting Machine, Logistic Regression, Random Forest, Decision Tree
 
**Files in my repo**

README.md, final_project_Ye.qmd file, final_project_Ye.html file, and BC_patients.xslx(raw case list generated by SEER*STAT).

<!-- Links -->
[forking]: https://guides.github.com/activities/forking/

