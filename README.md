# BreastCancerDetection
This project deals with determining whether the case is Benign or Malignant depending on the input values of the cells.

![Breast Cancer Information](https://www.nationalbreastcancer.org/wp-content/uploads/BC-Stats-v04_1-in-8-women-Landscape-1024x575.png)

Since the problem of breast cancer is increasing day by day this project aims in finding the number of women who have breast cancer depending on the values the input. 
There are many factors that may be responsible for breast cancer we need to identify which of them are responsible that can help in determining whether the person has breast cancer or not. 


In this project we have used various methods so as to first clear the data, scale the data, see the dependencies of the values on other columns as well as on the final column and finally compute if the person has cancer or not. 

![Dependencing using HeatMap](https://www.verywellhealth.com/thmb/aG43dcAugxoYrt6LL4R2bSYVyVM=/1500x1000/filters:no_upscale():max_bytes(150000):strip_icc()/breast-cancer-tumors-what-are-they-430277-v12-d91aad27f20b4f06aae6afc5a55868da.png)

In this project we were able to achieve very good accuracy of 98% on the test set on which the values were not trained. 
By using various methods like decision tree classifier, randomforestclassifier, logistic regression we found out that random forest classifier gave amazing results by giving only one incorrect prediction from the tested test set. 

![Dependencing using HeatMap](https://miro.medium.com/max/2228/1*UX4k8lSdBaKCDtsSlW7v8w.png)

Since only 1 information was incorrectly predicted and the result was of 98.6%, we can say that the model gave optimal results that was neither undefeated nor fitted but correctly predicted each and every test case.
