# Automation-Anywhere-Azure-Text-Analytics-API
Movie Review sentiment Analytics with A2019 and Azure APIs


I have tried to build an automation to analyse the sentiments of text whether it is any product review on movie review or any sort of text  provided to the Bot as an Input and with the help of  Text Analytics Azure APIs it will return a score from zero to one and Category of positive or negative.

The workflow of the Bot looks like:

We need to provide text file as an input.

The Bot  will create csv file as the output which contains the Review,Score and category of Review.

We will use the loop package of automation anywhere which will process each line of input text file.

With the help of rest API package of automation anywhere we are calling the Microsoft Azure API by providing header and subscription key and also the Request Body.

The output from API will be stored in the dictionary variable  which further used with string package of automation anywhere to get value of Score.
After getting the score we will take use of Advanced Excel package and set the review score and category variables to the Output file.

This will repeat for all the reviews in input file.

Finally I am displaying hte number of Positive and negative reviews in message Box.

This can be used to analyse the Feedback as well in different use cases.
