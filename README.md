# AI Project: Chatbot for tax certificate queries

## Background
A financial services provider has customers who make investments in various products (linked and unlinked). Customers earn income that includes interest, dividends, payouts, and annuities.
Certificates are issued to verify these payments for tax purposes – these are sent to customers and to the revenue authorities.

## Problem statement
During tax filing season, up to 2000 queries are received per day regarding :
outstanding certificates, incorrectly issued certificates, errors, and duplicates (90%);
technical queries about taxation and disclosure (10%).
These queries currently require a large number of call centre employees to divert them to the correct departments where relevant information can be retrieved.

## Solution
Introduce chatbots to deal with 90% of queries, thereby reducing time, effort and number of resources allocated to manning the call centre.

## Rationale for solution
A chatbot is an intelligent piece of software that can communicate and perform actions similar to humans.
For this problem, chatbots can automate most of the customer interaction by answering some of the frequent questions that are asked by customers. They are also able to connect to other online systems and databases, thereby retrieving information quickly and efficiently to provide immediate answers to many queries.

## Project details

Training the chatbot:
- The chatbot is trained on the dataset which contains categories, patterns and responses.
- A recurrent neural network is used to classify to which category the customer’s query belongs.
- A random response is given from the list of responses to train the chatbot.

Creating the chatbot:
- Import and load the data file
- Preprocess the data
- Create the training and testing data
- Build the model
- Predict the response
- Run the chatbot

See blogpost on this and similar projects at https://medium.com/@sayuri.moodliar/how-to-train-your-chatbot-and-other-modern-data-tales-783aa61630e6?sk=242abd3cd770c54709d3115ad03d2472

For further details on the project contact the owner.
