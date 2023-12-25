# 

# ML-Advanced-Regression-case-study
Build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
- [](#)
- [ML-Advanced-Regression-case-study](#ml-advanced-regression-case-study)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Problem statement](#problem-statement)
    - [Business goal](#business-goal)
  - [Conclusions](#conclusions)
    - [Model for **cnt** prediction](#model-for-cnt-prediction)
    - [Model for **registered** prediction](#model-for-registered-prediction)
  - [Technologies Used](#technologies-used)
  - [Contact](#contact)


## General Information
### Problem statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

### Business goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The company wants to know:
- Which variables are significant in predicting the price of a house.
- How well those variables describe the price of a house.

## Conclusions

### Model for **cnt** prediction


```cnt = 0.24 + 0.23xyr -0.06xholiday 0.05xweekday 0.02xworkingday 0.49xtemp -0.12xhum -0.18xwindspeed -0.25xlight_snow -0.06xmist -0.07xspring 0.04xsummer 0.09xwinter```

```
Dep. Variable:                    cnt   R-squared:                       0.834
Model:                            OLS   Adj. R-squared:                  0.830
Method:                 Least Squares   F-statistic:                     207.4
Date:                Mon, 20 Nov 2023   Prob (F-statistic):          1.00e-184
Time:                        12:48:21   Log-Likelihood:                 495.78
No. Observations:                 510   AIC:                            -965.6
Df Residuals:                     497   BIC:                            -910.5
Df Model:                          12                                         
Covariance Type:            nonrobust                                         
```


### Model for **registered** prediction
```registered = 0.24 + 0.25xyr 0.14xworkingday 0.38xtemp -0.11xhum -0.15xwindspeed -0.25xlight_snow -0.05xmist -0.1xspring 0.09xwinter```

```
Dep. Variable:             registered   R-squared:                       0.840
Model:                            OLS   Adj. R-squared:                  0.837
Method:                 Least Squares   F-statistic:                     290.7
Date:                Mon, 20 Nov 2023   Prob (F-statistic):          2.52e-192
Time:                        12:48:57   Log-Likelihood:                 497.06
No. Observations:                 510   AIC:                            -974.1
Df Residuals:                     500   BIC:                            -931.8
```


## Technologies Used
- python - version 3.10.13
- appnope- version 0.1.3
- asttokens- version 2.4.1
- backcall- version 0.2.0
- comm- version 0.1.4
- contourpy- version 1.1.1
- cycler- version 0.12.1
- debugpy- version 1.8.0
- decorator- version 5.1.1
- exceptiongroup- version 1.1.3
- executing- version 2.0.0
- fonttools- version 4.43.1
- gc-report-libs- version 2.5.5
- ipykernel- version 6.26.0
- ipython- version 8.16.1
- jedi- version 0.19.1
- joblib- version 1.3.2
- jupyter_client- version 8.5.0
- jupyter_core- version 5.4.0
- kiwisolver- version 1.4.5
- matplotlib- version 3.8.0
- matplotlib-inline- version 0.1.6
- nest-asyncio- version 1.5.8
- numpy- version 1.26.1
- packaging- version 23.2
- pandas- version 2.1.2
- parso- version 0.8.3
- patsy- version 0.5.3
- pexpect- version 4.8.0
- pickleshare- version 0.7.5
- Pillow- version 10.1.0
- platformdirs- version 3.11.0
- prompt-toolkit- version 3.0.39
- psutil- version 5.9.6
- ptyprocess- version 0.7.0
- pure-eval- version 0.2.2
- Pygments- version 2.16.1
- pyparsing- version 3.1.1
- python-dateutil- version 2.8.2
- pytz- version 2023.3.post1
- pyzmq- version 25.1.1
- scikit-learn- version 1.3.2
- scipy- version 1.11.3
- seaborn- version 0.13.0
- six- version 1.16.0
- stack-data- version 0.6.3
- statsmodels- version 0.14.0
- threadpoolctl- version 3.2.0
- tornado- version 6.3.3
- traitlets- version 5.12.0
- tzdata- version 2023.3
- wcwidth- version 0.2.8


## Contact
Created by [@irish-luong] - feel free to contact me!

