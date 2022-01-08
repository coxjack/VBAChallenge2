# Election Analysis
Challenge 2 for Butler Data Science

## 1. Overview of project
### 
* Our goal in this project was to gather and analyze stock data from 2017 & 2018 and help our subject 
decide which Green Energy stocks should be invested in. We had data for 12 different stocks. The data included for these stocks was the ticker name, the date of market activity for each stock, opening price, closing price, the daily high, the daily low, adjusted closing price, and the daily volume. In the second part of this project our goal was to streamline our code to become more efficient.

## 2. Results
###
* On the whole the stocks performed better in 2017 than in 2018. Only tickers "RUN" and "TERP" performed better in 2018 (RUN up from 5.5% to 84% return, TERP up from -7.2% to -5% return).

![2017 Stock Performance](https://github.com/coxjack/VBAChallenge2/blob/main/Additional%20Supporting%20Images/2017%20All%20Stock%20Refactored%20Results.png)
![2018 Stock Performance](https://github.com/coxjack/VBAChallenge2/blob/main/Additional%20Supporting%20Images/2018%20All%20Stock%20Refactored%20Results.png)

* The refactoring of our code has lead to significantly improved runtimes. A 2.6 second improvement for 2017 and a 4.31 second improvement for 2018.

**2017 Original Performance**

![2017 Original Performance](https://github.com/coxjack/VBAChallenge2/blob/main/Additional%20Supporting%20Images/2017%20Original%20Code%20Time.png)

**2017 Refactored Performance**

![2017 Refactored Performance](https://github.com/coxjack/VBAChallenge2/blob/main/Resources/VBA_Challenge_2017.png)

**2018 Original Performance**

![2018 Original Performance](https://github.com/coxjack/VBAChallenge2/blob/main/Additional%20Supporting%20Images/2018%20Original%20Code%20Time.png)

**2018 Refactored Performance**

![2018 Refactored Performance](https://github.com/coxjack/VBAChallenge2/blob/main/Resources/VBA_Challenge_2018.png)

*This improvement was achieved by refactoring the code as below.

![Refactored code](https://github.com/coxjack/VBAChallenge2/blob/main/Additional%20Supporting%20Images/Refactored%20Code.png)

## 3. Summary
###
* The advantages of refactoring a code are that not only do you get improved code runtime as shown above, but also refactoring code can make it more clear and succinct for any reader of the code. Being able to write clear and quick performing code is the goal of any programmer.
*The main disadvantage to refactoring code is that you do not always know it is going to be successful. You may spend time trying to change already successful working code and you may either come up with code which actually runs slower or even code that doesn't run at all.
*For this specific task the pros were clear as we were able to improve the runtime of our code and make it easier and more clear to follow. The cons do not apply in this case because we were able to successfully improve the code.