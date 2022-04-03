# 14
This project generates a trading signal using short and long moving average, then compares cumulative returns using an SVM model and logistic regression.

Technologies The project is written in python 3.9 and uses the pandas, numpy, matplotlib, pathlib, hvplot and sklearn.

Installation Guide Users may run the program in an IDE of their choice.

Usage Users upload a csv of historical closing prices in a dataframe, then calculate short and long moving averages. A buy or sell signal is generated based on the SMAs and strategy returns are compared with historical returns. Then users apply SVM model and logistic regression models to generate trading signals on the same data set.

Contributors The project was completed by jbena4 under the direction of instructors with the Columbia Engineering certificate program.

License This project is free to distribute and licensed under MIT.

Original crossover strategy:

![image](https://user-images.githubusercontent.com/86986786/161440230-b1a7217c-97c5-488e-95ba-f2fb9afe27bd.png)

SVM model:

![image](https://user-images.githubusercontent.com/86986786/161440260-6220d667-2359-43d9-a363-92d598ae86c2.png)

Logistic regression model:

![image](https://user-images.githubusercontent.com/86986786/161440285-fb657d0f-e378-41bf-860d-5477771c5296.png)

