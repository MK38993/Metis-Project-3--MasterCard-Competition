# METIS PROJECT 3: PROJECT WRITE-UP

## MasterCard's Merchants

## Abstract
The goal of this project is to construct a model that will estimate the costs and benefits of marketing MasterCard's products to different merchant demographics.
After datasets provided by Data.gov and the US Census Bureau, as well as press releases from MasterCard and some of its competitors, I found that the economies of Massachusetts and New Jersey appear to have particularly strong retail sectors. However, this is just preliminary EDA; additional data from MasterCard is required to construct the model.

## Design
MasterCard has enjoyed strong growth, has weathered the COVID pandemic without losing market share, and is well on its way to recovery. However, PayPal, a potential competitor, has benefitted greatly from the pandemic and the subsequent shift to e-commerce; its purchase volume has nearly doubled in the past two years. 

MasterCard has three marketing options to expand its network: it can market to consumers, to merchants, or to card issuers - banks.

None of these markets are fully penetrated yet; but I chose to market to merchants specifically; I sometimes see stores that don't accept credit/debit cards - only cash. How could MasterCard find merchants who are likely to respond to marketing?

Suggested solution path/Model:
Build a regression algorithm that predicts the return on investment when marketing to different merchant demographics. It would require the following data:
1. Merchant information - what characteristics (business size/sector/location) is corellated with them accepting credit cards?
2. Transaction data - what demographic does the merchant serve, and how might this affect his/her view of credit cards?

Measures of success:
Technical: The model achieves a high r2 coefficient, and can be used to market to merchants likely to join MasterCard's network.
Non-technical: MasterCard's growth accelerates. Growth can be defined in terms of merchants accepting their cards, consumers using their cards, or even the amount of money that passes through MasterCard's system.

## Data
For my preliminary EDA, I picked multiple sources of data and combined them to gain more insight into state vs. national economies.
My primary data source was a consumer spending dataset from data.gov, which provides near-daily consumer spending for several retail sectors in the states of CT, MA, NJ, NY, and RI, indexed to Jan 1 2020.
My secondary data source was a summary of retail sectors, nationwide, aggregated to provide monthly estimates of each sector and its subsets.
Finally, I used press releases from MasterCard, Visa, CapitalOne, and PayPal to determine the growth in their payment volume over the past 8 business quarters.


## Algorithms
##### Cleaning/EDA
I used Google Sheets to clean, aggregate, and interpret data.

Links to the Sheets workbooks can be found below.

https://docs.google.com/spreadsheets/d/1vRaOhZIWY7D7Dmri9p_9iX0pG4vyQ2TLsnNy-Q5UC6g/edit?usp=sharing
https://docs.google.com/spreadsheets/d/1x5SFdYWWykaKbzTvjw2F8wq6aT8igIE1ZAxMaOCO5Nc/edit?usp=sharing
https://docs.google.com/spreadsheets/d/1YKP5DmGJFU70kJ1ExjoU6GN45gufYb4M_vV0VOEltOg/edit?usp=sharing
##### Aggregation
For my primary dataset, I averaged growth/loss for each retail sector over each month using pivot tables. These tables are imported into Tablaeu.

##### Visualization
Links to the Tablaeu workbooks and dashboards can be found below:
The dashboard showing the volatility of smaller states can be found [here](https://public.tableau.com/app/profile/matt.k1804/viz/Metis3MACompetition/RecessionRecovery?publish=yes).
The dashboards showing how different states compare to each other for different retail sectors can be found [here](https://public.tableau.com/app/profile/matt.k1804/viz/Metis3MACompetition/RecessionRecovery?publish=yes).

## Tools
1. Excel for data cleaning, aggregation, and analysis
2. Tableau for creating visualizations

## Communication
In addition to the slide presentation, which can be found [here](https://docs.google.com/presentation/d/1wRh7ijjPt8EI46xX4Au0aZUUAuPR9FK39UN7HvDB1k4/edit?usp=sharing), the Tablaeu visualizations can be found above.
