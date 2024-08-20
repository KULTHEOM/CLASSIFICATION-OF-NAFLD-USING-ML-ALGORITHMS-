# CLASSIFICATION-OF-NAFLD-USING-ML-ALGORITHMS-
Non alcoholic fatty liver disease is a serious medical disorder . In this project i have classified different stages of NAFLD using various machine learning classification algorithms such as Random forest , histgradient boost , gradient boosting  , logistic regression . Out of which random forest algorithm gave the best accuracy which was feasible for medical datset . 

Flow of model :

![image](https://github.com/KULTHEOM/CLASSIFICATION-OF-NAFLD-USING-ML-ALGORITHMS-/assets/142748736/ba8fea84-fd4d-4d59-a664-e9290c3ce710)


Dataset parameters :

Dataset which contained both clinical and demographic data of patients we dropped parameters such as: Fibrosis cat, Steatosis cat, Ballooning cat, Lob Infl cat and took parameters such as: Fibrosis score, Steatosis score, Ballooning degeneration score, Lob. Inflm score, Age, Gender, Weight, Body mass index (BMI), Diabetes mellitus (DM), DYSLIPIDE, Haemoglobin (HB), TLC, PLT, NLR, Albumin, Serum Alkaline Phosphatase, Serum ALT/SGPT, Serum AST/SGOT, Serum Bilirubin Direct, Serum Bilirubin Indirect, Serum Bilirubin Total, Serum GGT, Serum Urea, Serum Creatinine, Serum Uric Acid, Serum Cholesterol, Serum Triglycerides, Serum HDL Cholesterol, Serum LDL Cholesterol, TNF Alpha, TSH for training our model. The target variables set were EARLY NASH, NASH AT RISK, ADV FIBR. 


Data cleaning :

Various data imputation techniques were tried out of which multivariate imputer gave the best results .

Model traning :

Different machine learning classification models were applied to dataset out of which Random forest gave the best possible accuracy of 68.68%. 

Accuracy :


Random forest algorithm gave the best possible accuracy and feasible results in plot of learning curve also. 

![image](https://github.com/user-attachments/assets/dfbcb90d-509c-499d-adfd-a02491efdec1)










