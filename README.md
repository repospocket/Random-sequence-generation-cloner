# Random sequence generation cloner
The database is manually put together using around 700 old winning numbers that are padded with class '1'. None winning numbers are added at the end by code and padded with class '0'.  
A winning number is a finite random sequence of seven numbers from 1 to 50.  
Logistic regression is the (first) model used to fit the database and predict if a new random sequence pass or fail as a possible winning number in a future draw.  
(in independent probability all numbers are equally likely to win and a new event is not affected by the outcome of past or future events).  
1. Open a terminal or command prompt in the directory.  
2. Type "python .\lotto.py" and press enter.  
![image](sc1.jpg)  
