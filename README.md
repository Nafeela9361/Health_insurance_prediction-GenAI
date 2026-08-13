# 🏥 Health Insurance Premium Prediction
This study presents a machine learning approach for predicting health insurance premiums based
on individual demographic and health-related characteristics. The main objective is to predict
insurance charges using variables such as age, BMI, number of children, sex, smoking status and

region. It also examines how incorporating additional relevant features influences the predictive
performance of the model.
The analysis starts with data exploration and preprocessing. The categorical variables sex,
smoker and region are transformed into numerical representations using dummy encoding. The
variable charges is considered as the target variable. The dataset is divided into training and
testing sets using a 70:30 ratio, producing 935 training records and 402 testing records.
Three Linear Regression models are constructed with increasing numbers of features. Model 1
uses age alone, Model 2 uses age and BMI, while Model 3 incorporates all available numerical
and encoded categorical variables. This progressive modeling approach helps evaluate the
contribution of additional features to insurance premium prediction.
The results show that using age alone provides limited predictive performance, with a test MSE
of approximately 154.52 million and an R² of 0.097. The prediction performance improves when
additional variables are incorporated into the model. This indicates that insurance charges are
influenced by several demographic and health-related factors. Overall, the study demonstrates
the importance of selecting relevant features and appropriately encoding categorical variables for
improving regression-based premium prediction.
