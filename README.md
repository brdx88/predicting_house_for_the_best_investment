# Predicting House Price for the Best Investment

![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/house.jpeg)

Home is a primary basic need, everyone needs a house for shelter every day. However, for those who have their needs met, some people use the money to invest. One of the investment instruments is property, especially houses. This dataset provides information on the number of bedrooms, bathrooms, conditions, views, building area, land area, basement area, and of course prices. The dataset can be found on [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction).


## Problems
Many people want to start investing but don't know where to invest. Property is one of them. But the question is, what kind of house is roughly compatible with the money owned by investors? Is asking a property agent a solution? Truth be told, real estate agents will only convince you to buy their wares. Not convincing you to invest. When it comes to investing, you need to know what specifications the market will be interested in. You don't buy just to be deposited, do you?

## Goals
Before you spend a lot of money on investing, you should consider the specifications first rather than listening to the empty sentences of real estate agents. High risk high return, but investing is about minimize risks to increase the chances of getting big returns constantly. We will make Machine Learning model to predict house prices so that at least we know the market price in circulation with specifications that match the price.

## Exploratory Data Analysis

![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/0.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/1.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/2.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/3.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/4.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/5.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/6.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/7.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/8.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/9.png)
![1](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/images/10.png)

## Conclusions
1. **Average of house price** is 540,088 from range 75,000 until 7,700,000 .
2. **Obvious factors that makes house price either high or low** are area bedrooms, living space area, floors, condition, grade, and property's view.
3. **Most houses sold with 3 bedrooms and 4 bedrooms.** 46% houses sold with 3 bedrooms, 32% houses sold with 4 bedrooms, and 13% houses sold with 2 bedrooms.
4. **Most houses have 2 bathrooms without shower inside** with 25%. The second one, 18% houses have only 1 bathrooms. Most buyers prefer to choose whether house with 1, or 2 bathrooms.
5. **42% houses sold by grade 7** out of 13 which means great enough, not perfect but not bad tho.
6. **60.7% houses are sold without basement level.**
7. **Houses which built in 2000s are the top 10 house sales** like 2003, 2004, 2005, 2006, and 2014.
8. **65% houses were sold by good condition 3** of 5 points.
9. **90% property's view valued by 0 points were sold.**
10. **The house price tend to be cheaper when sqft_living is smaller.**

## Recommendations
1. As a property investor, we could prepare up the money minimum 540,888 to have a not so bad property.
2. Keep in mind that there are important things to be focused on before you buy or invest in property like number of bedrooms, area of living space, number of floors, condition, grade, and property's view. Without basement it's okay though because 60.7% houses are sold without basement level.
3. If you may, find house with 3 or 4 bedrooms to increase your chance when you want to sell your property.
4. Find a house that has grade 7 out of 13. This means you won't waste your money too much because most buyers tend to find a great house to live not to show off.
5. Find the house which has condition score 3. It's enough because there's a lot of market who buy house with that condition.
6. Nevermind the property's view, because 90% property's view valued by 0 were sold.
7. We could offer some Machine Learning model to predict the house price. Our ML model can predict with its accuracy 89%. You can find some good houses with the best price and the best specification without worry.


#### Fore more insights, please visit the notebook [here](https://github.com/brdx88/predicting_house_for_the_best_investment/blob/main/king_county_house.ipynb)
