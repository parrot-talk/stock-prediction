# ml2
Here the main goal of this program is to trade, so that user benefits.

This has been divided into three parts:
1.Model that predicts the outcome
2.Program that sends email to user to notify buy and sell
3.CSV file where all the stocks data are stored

1.Model that predicts the outcome:
	Here all the historical value of currencies are collected, their operation is performed by selecting only the ceratin data, to make the model more accurate and also remove the 
inflations influence.
Then random forest classifier is used for making the prediction of tomorrow.
And by using precision we can see that our model predicts more than 50% accurately.


2.Program that sends email to user to notify buy and sell:
	Here the email function is set up with sender email and password, along with receivers email.
It sends the email when the function is callled.


3.CSV file where all the stocks data are stored:
	Here all the stocks that we were supposed to buy and notified to user is saved and when the price is more than +10% of what we bought or -5% of what we bought it sends email to 
sell al the stocks and remove it from file, while if it is more than +5% of what we bought or -2.5% of what we bought, then it sends an email to sell half of it! But it is not deleted from file.
This reduces the loss and increses the profit.



HERE:
'EURUSD =>EURO USD
 GBPUSD => POUND USD
 USAU =>GOLD USS
