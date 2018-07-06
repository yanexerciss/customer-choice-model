# customer-choice-model
#### Introduction

Using Dominick’s consuming data set to explore relationship between price and customer purchase choice using discrete choice model and instrumental variable approach. Interpret and compare different models and elasticity.



#### Dataset

Dominick's database(https://research.chicagobooth.edu/kilts/marketing-databases/dominicks) includes over nine years store-level scanner data at Dominick's Finer Foods for more than 3,500 UPCs. In this study, we will only focus on **Refrigerated Orange Juice Category**. It contains 121 weeks sales and prices for top 6 brands and other small brands. The data files we will use are:

1.  refre_juice_sales.csv (*including product and transaction information*)
2. zone.csv (*including store and zone information*)

The dictionary of refre_juice_sales.csv shows below:

![](C:\Users\Yan Li\Desktop\dictionary.PNG)



#### Analysis Steps

1. Data overview to have a brief picture of variable distribution and brand sales trend.
2. Data manipulation as the preparation of model building.
3. Model Building to build different OLS and IV (Instrumental variable approach) models.
4. Model result, choice and interpretation
5. Comparison with other research papers in terms of parameters choosing and elasticity.