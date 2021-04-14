# Insurance-charges
The dataset used contains various features such as age, sex, smoking habits, region etc. of individuals along with their respective insurance charges. The model applies multiple linear regression to predict the insurance charges and the accuracy is measured with the R2 score.
Before starting with the model, we performed exploratory data analysis in Tableau to check for correlations. 

![alt text](https://user-images.githubusercontent.com/72266307/114744578-77172880-9d6b-11eb-9cac-b3d5fa66904f.jpg)

As we can see, charges increase with age and hence there is a positive correlation.

We performed similar analysis with region,sex and smoking as well to find:

![alt text](https://user-images.githubusercontent.com/72266307/114746315-391b0400-9d6d-11eb-8a4a-f2c854b2b176.jpg)

![alt text](https://user-images.githubusercontent.com/72266307/114746030-e7727980-9d6c-11eb-8643-36ebd5f78577.jpg)

![alt text](https://user-images.githubusercontent.com/72266307/114746422-5bad1d00-9d6d-11eb-9fda-04a3b86d4a4d.jpg)

Thus, we concluded that region and sex did not have much effect on the deviation of charges. 
Smoking was one of the leading factors in explaining the deviation in charges.

The model was based on the features: age, children, bmi and smoking. R2 value was found to be 0.78

