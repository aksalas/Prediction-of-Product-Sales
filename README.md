# Prediction of Product Sales
## Author: Arvin Kenneth Salas
# Business Problem:
We are finding the best predictors to improve item sales for grocery store organization
# Data Dictionary
![Data Dictionary](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/0576e26e-9a26-4573-a173-6238514939df)
# Explanatory Values
## The maximum item price of the product is strongly correlated with the item sales

![Heatmap](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/aa49e07a-dca4-4e81-809b-a080f38f4420)
- Here we see that the Item's Retail Price has one of the strongest correlations with Item sales.
- Other data values have little to no correlation with item sales

![Item type vs outlet sales](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/b16b0f97-410f-4121-94b4-26ab8760ae77)
- All of the items appear to have the sell about 2$,500,000 across all stores
- Here we see that seafood yields the most sales per product for each grocery store

# Model Evaluations
![Linear Regerssion Model](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/621106fb-bd35-497c-b993-a199716f78b4)
- Our model predicts that if the product sold in a grocery store , it will reduce its sale by $ 2000.
- The model also predicts that if the store is a type 3 supermarket, then the sales would increase by $ 1200 per count.
- Lastly, the model also predicts that the item visibility of items will reduce the sales by $ 266.

![Decision Tree Feature Importance](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/5aca3074-14ff-4bab-885e-81ea62c63f41)
- The top 5 most important features are item mrp, grocery outlet type, item visibility, item weight, and supermarket outlet type.

![Summary Bar Plot](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/c70459b7-8546-40f5-a3ca-321eeb598ca3)
- This model has item visibility as a lower influence on the model's ability to the previous model.
- for the most part, the features are relatively the same.

![Dot Plot](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/f6a64b8f-7c82-4f1a-b711-b00516bd01ad)
- The higher the MRP on the item, the higher the predicted item sales
- Grocery store types have lower predicted item sales compared to supermarket
- The lower establishment year, the lower the predicted item sales

![High Sale](https://github.com/aksalas/Prediction-of-Product-Sales/blob/main/high_sale_explanation.png)
- The most heavily influenced feature for this product is that it is sold in a grocery store.
- the second highest influencer is the products MRP
- 
![Low Sale Force Plot](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/66cb5817-a3c6-4289-850f-00a82089c6c3)
- The most heavily influenced feature according to the force plot is that it is also sold in a grocery store.


# Predictor Model
## Regression Metrics for the predictor
![Regression Model Metrics](https://github.com/aksalas/Prediction-of-Product-Sales/assets/95392861/9f06858f-d83b-4dd7-9be3-893fbc1f3c5e)
- We used a Random forest model to predict item sales.
- The R-Squared for the testing data is 0.59 and an MAE of 732.
- These metrics mean that our model can predict how much an item would sell with a variance of .59 from the target price.
# Reccomendations
- Further optimization is needed to reach a more desirable model that can predict sales.
# For any additional questions, please contact arivnkennethsalas@gmail.com
