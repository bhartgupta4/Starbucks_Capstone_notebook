# Starbucks_Capstone_notebook

## Installation
1 Pandas
2 Scikit learn
3 Matplotlib and seaborn
4 Pandas

## Dataset used
Data Sets
The data is contained in three files:
· portfolio.json — containing offer ids and meta data about each offer (duration, type, etc.)
· profile.json — demographic data for each customer
· transcript.json — records for transactions, offers received, offers viewed, and offers completed
Here is the schema and explanation of each variable in the files:
portfolio.json
· id (string) — offer id
· offer_type (string) — type of offer ie BOGO, discount, informational
· difficulty (int) — minimum required spend to complete an offer
· reward (int) — reward given for completing an offer
· duration (int) — time for offer to be open, in days
· channels (list of strings)
profile.json
· age (int) — age of the customer
· became_member_on (int) — date when customer created an app account
· gender (str) — gender of the customer (note some entries contain ‘O’ for other rather than M or F)
· id (str) — customer id
· income (float) — customer’s income
transcript.json
· event (str) — record description (ie transaction, offer received, offer viewed, etc.)
· person (str) — customer id
· time (int) — time in hours since start of test. The data begins at time t=0
· value — (dict of strings) — either an offer id or transaction amount depending on the record

## Project Overview
In this project, an attempt has been made to analyse how Starbucks customers use the app. The promotion for starbucks using various offers and are these offers actually helpful. The data sets used in this project contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. The customer's behaviour has been attempted to analyse based on the dataset.

## Result
An attempt has been made to analyse the dataset of Starbucks and understand the data and make model to predict how a customer will take the offer whether the offer will be received or not and if received whether it will be completed. Firstly the data is analysed and explored and relation between different variables is understood with the help of graphs. The distribution of variables in the datasets, what types of customer base is there and gender wise distribution of the customers based on their income and how many customers receive the offer and how many of them complete it. It is found that more number of Females complete offers compared to males with 56% females complete the offer of what they receive compared to 43.18% among males but males receive more offers than females. The scenario completely changes for transactions which is 72794 among males and 49382 among females. Further exploration was made on which offer is being received better by the customer. Hence females could be given more offers further offer id fafdcd668e3743c1bb461111dcafc2a4 should be more distributed compared to others since it is completed a greater number of times.

The findings of this analysis can be found here https://medium.com/@bhartlive12/starbucks-customer-analysis-5a6753fa29ca
