# Hack1_Online_Retail

**Hack1_Online_Retail** is detailed analysis of online retail data.  The goal is to analyse online retail transaction data to understand customer behaviour, identify popular products, and optimise pricing and marketing strategies. The aim is to provide insights into customer behaviour, popular products, and pricing strategies to improve sales and marketing efforts for the customer.  The analysis will include data visualisations in Matplotlib, Seaborn and Plotly. 

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The data set to be used is retail online data that has been sourced from  https://www.kaggle.com/datasets/abhishekrp1517/online-retail-transactions-dataset.

The data set includes orders from 38 Countries.
The data set include approx 25900 unique orders and 541910 order lines.


## Business Requirements
* The Business requirements are to identify the following 
Exclude non product items
Product quanties between 1 and 6000
Highest unit price 700
Indentify most popular product and show seasonality



## Hypothesis and how to validate?
* Jam making most popular in UK    -  This will be identifies by analysing the distribution of jam making products by country. Only UK orders were analysed the volumes of non UK order were too low to be considered. 91 % of order were from the UK.

Union jack products most popular in the UK -  This will be identified by analysing the distribution of union jack products bycountry - This was proved true.

Homeware was the most popular product


## Project Plan
* CLean data
* Create visualisations
* Test visualisations
* Crate interactive visualisations ( I couldn't get this to work)

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* I looked at geographical analysis of the data an found it was not suitable 
* I created product groups to help categorise the products
* I used chat GPT to help categorise the products to save time
* showed product groups over time based graphs to identify seasonality


## Ethical considerations
* There is no customer detail that can be traced to an individual.  Customer ID is used but


## Unfixed Bugs
* The final dashboard has the following bugs  ValueError: Mime type rendering requires nbformat>=4.2.0 but it is not installed


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* Code Instritute training materials
* I used chat GPT to help with fixing errors and to help with interactive graph and data cetegorisation


## Acknowledgements (optional)
* I would lie to thank Vasi for his help and guidance
* I would lie to thank Mark and Neil for there demonstrations of knowledge
* Lee Merchant and Teresa for their support and encoragement