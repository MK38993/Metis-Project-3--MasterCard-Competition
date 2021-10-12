# Metis Project 3: MasterCard's Competition - MVP 

### Analyzing economic recovery in the U.S.


#### The problem
While MasterCard easily outstrips its main competitor, Visa, it faces rapidly-growing competition from PayPal, which has flourished during COVID due to the ease with which it provides online payment services.

MasterCard is by no means stagnating, but is still looking to find more merchants, customers, and banks to expand its network.

My proposed data science solution is to utilize MasterCard's proprietary datasets to pinpoint which locations/countries/business types/demographics/consumer purchase segments play the largest part in predicting its performance, as well how well marketing to different economic sectors (e.g. apparel, groceries, luxury, restaurants) can improve growth


### The project
The goal of this project is to determine which factors affect MasterCard's key performance indicators such as card ownership, transaction volume, and overall earnings. The following outline details my progress towards conducting preliminary EDA.

To achieve this goal, I collected consumer spending data from [data.gov](https://catalog.data.gov/dataset/percent-change-in-consumer-spending-january-2020-through-the-present). While I was only able to acquire data for five states on the East Coast, I believe this is enough data to conduct initial EDA.

Using Tablaeu, I displayed:
1. The furthest spending drop at the height of the pandemic.
2. The highest spending rebound during recovery from COVID. 
3. The change in consumer spending by state.
4. The change in each aspect of consumer spending, for each state.

![Alt text](https://raw.githubusercontent.com/MK38993/Metis-Project-3--MasterCard-Competition/main/max_drop_state.png "Fig.1")
![Alt text](https://raw.githubusercontent.com/MK38993/Metis-Project-3--MasterCard-Competition/main/max_growth_state.png "Fig.2")
![Alt text](https://raw.githubusercontent.com/MK38993/Metis-Project-3--MasterCard-Competition/main/total_spending_state.png "Fig.3")
![Alt text](https://raw.githubusercontent.com/MK38993/Metis-Project-3--MasterCard-Competition/main/ct_spending_categories.png "Fig.4")


In their "SpendingPulse" press releases, MasterCard outlines the industries that have grown the most across the entire US. Comparing their "SpendingPulse" metrics with the East Coast data allows us to calculate which sectors in a state may be particularly strong. This gives insight into:
1. Which merchants to market to in a particular state
2. What sectors to offer cardholders rebates to in a particular state


The data can be found in [this](https://docs.google.com/spreadsheets/d/1vRaOhZIWY7D7Dmri9p_9iX0pG4vyQ2TLsnNy-Q5UC6g/edit?usp=sharing) Google Sheets workbook.


