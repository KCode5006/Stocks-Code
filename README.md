# Stocks-Code
Python script to quickly track trading strategies (currently set to 50k allocated as an example amount):

This code is used as a daily check in on my strategies.  
It will:  
-Check if the strategy is on or off (ex. did the price cross over a moving average)  
-Highlight changes in strategies (which will notify me I need to make a trade)   
-Tells me how many shares to buy based on volatility adjusted allocation  
-Tells me if there is low allocation resolution because of share size (ex. allocate 1000 to meta but one share is ~700 --> means a large % unused)

note:  
-I did use ChatGPT to help write this but with the older 2024 versions.  
-This calls another function file I created called Indicators_TS. 

This is used in conjunction with a different script which scans for good strategy opportunities.
