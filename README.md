# Twitter-Analysis
I extracted tweets about user choice from twitter API and found the sentiment of each tweet .
Buil the model to predict the sentiment of the tweets using NLP .

To Increase the accuracy did some feature engineering by adding attribute gender which is not available while extraction . 
Myself created a database of names both indian and foriegn names .
Created my own vectorization algorithm in Gender_prediction_by_name.py file to classify male or female on their twitter name . Actuallt it improved the accuracy by 6%.

#Logic for gender prediction by name :-

Most of the female names end with vowels (a,e,i,o,u) and almost every female name doesn't start after T . 
There are more vowels character in female name . Used the formula (lenght of name)/(no of vowels)
Used all the above logic to create my vectorization . 
Used Gradient Boosting algorithm it predicted with an accuracy of 75% .



