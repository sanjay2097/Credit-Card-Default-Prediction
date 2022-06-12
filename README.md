# Credit-Card-Default-Prediction
![1_hAMUkRqnWVn4fxTjCNJP1w](https://user-images.githubusercontent.com/98027899/162555335-b2686f0c-0547-4886-a50a-ba11428631de.jpeg)

### Objective : 
### The economic construction of large- and medium-sized cities, which not only improves people’s living standards but also changes people’s consumption concept and consumption mode. People are more and more inclined to spend ahead of time and mortgage their “credit” to the bank to enjoy certain things in advance. However, when consuming, people often lack rational thinking and overestimate their ability to repay loans to banks in time.

### In this project, we build a predictive model that could predict the risk of credit card defaults on the basis of information on default payments, demographic factors,credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005. Upon initial inspection, we found that only 16.3% of the clients in the dataset had defaulted which we balanced for training set using SMOTE.We used sklearn pipelines to build our classification model.

![image](https://user-images.githubusercontent.com/98027899/173230056-1ecb80a7-291a-4acb-88cd-dff683812899.png)

### Project Details :

### Distibution of categorical features
![Screenshot 2022-06-12 152212](https://user-images.githubusercontent.com/98027899/173229729-4bb2e554-b9c5-47f8-9b34-a07c4e56496a.png)

### Distibution of continous features
![download](https://user-images.githubusercontent.com/98027899/173229751-9e414336-0e12-4e7a-a315-c5c92c479724.png)

### Boxplot for visualizing outliers
![download (1)](https://user-images.githubusercontent.com/98027899/173230165-377a25dd-17ce-4730-b6ef-f13972a0f104.png)


### Feature selection using feature importance
![download (2)](https://user-images.githubusercontent.com/98027899/173229819-e1df20a0-38ee-4c8c-a4d2-ae129c2725b6.png)

### Model performance
* ### Baseline
![Screenshot 2022-06-12 162310](https://user-images.githubusercontent.com/98027899/173229867-9abbc294-122e-445c-a5d0-46045660b992.png)

 * ### Hyperparameter Tuned
![Screenshot 2022-06-12 162341](https://user-images.githubusercontent.com/98027899/173230101-72dd22a4-fb55-4767-a227-aa2116b02a7a.png)

![image](https://user-images.githubusercontent.com/98027899/173230056-1ecb80a7-291a-4acb-88cd-dff683812899.png)

### Conclusion :

### We developed an ensemble binary classification model using the XGBoost and Random Forest algorithm to predict whether clients will default based on past finances and demographic factors. Hyperparameter tuned Random Forest gives us the highest Recall score of 81% and AUC-ROC score of 87%.

![image](https://user-images.githubusercontent.com/98027899/173230056-1ecb80a7-291a-4acb-88cd-dff683812899.png)

### Scope :
### Default prediction models can be successfully employed in banks for early prediction whether a bank client is going to default on his payments and this would conserve bank resources namely time and assets. We can use the insights from this project to gauge the financial health of our clients and decide how much credit we can extend to them. This will help to avoid the case of bad debts which will save banks unexpected losses.

![image](https://user-images.githubusercontent.com/98027899/173230056-1ecb80a7-291a-4acb-88cd-dff683812899.png)

### References :

https://ieeexplore.ieee.org/document/8776802

https://www.researchgate.net/publication/344914401_An_Investigation_of_Credit_Card_Default_Prediction_in_the_Imbalanced_Datasets
