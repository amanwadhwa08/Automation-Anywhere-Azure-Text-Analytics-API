I have built an automation to analyse the sentiments of the input text weather it is movie reviews,email message,product reviews etc provided in the text file with new line as delimiter. 
It gives a numeric score between 0 and 1. Scores close to 1 indicate positive sentiment, while scores close to 0 indicate negative sentiment. A score of 0.5
indicates the lack of sentiment (e.g. a factoid statement). I have used Text Analytics API provided by Azure.

We need to pass input text files with each line as review or any text to predict sentiments.

Output file will be created in csv format with score and category.



