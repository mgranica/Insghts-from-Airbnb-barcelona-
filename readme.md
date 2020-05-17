# Airbnb insights from Barcelona
<img src=jpg\bcn_gotic.jpg>
To visit the medium blog spot clik [here](https://medium.com/@migue.granica/airbnb-insights-from-barcelona-in-covid-19-times-201bbd81b32c)


## Dataset

The data consists of information regarding 21,000 listings from the city of Barcelona.  including
price, carat, and other diamond qualities. The dataset can be found in the

To do the study, we extract the datasets from the page insideairbnb.com. 
All the listings divided into different types of content are registered in it. 
for it we will download 2 datasets: calendar and listings (we decided to use 
the limited listings since with the information it contains we can answer our problems)

- calendar: indicate the price and availability of eache listing during the all year.
it has 7 million rows and 6 columns
- listings: provides us with specific and specific information about the publications. 
21000 rows contains all the publications of the city of Barcelona and information on the location, 
the type of accommodation it offers, what reviews it has, who is its host and others.


## Motivations
Understand CRISP-DM work methodologie. Apply it to real case scenario.
    - business understanding: understand the problems
    - Data understanding: move the questions from business to data
    - Data Preparation: involve find the right 
    - Modeling: instatiate, fit, predict, score
    - Deployment: deploy solutions
    

- Firstly, would it be interesting to see how the price of the listings varies throughout the year? and what relationship does it have with availability? After 2 months of confinement and social seclusion, the consequences of COVID-19 are already expressed in these values. 
- Also, how do airbnb listings vary by neighborhood? They have the same impact in the different neighborhoods of the city? What consequences has it had on the rental housing market?
- Finally, on the other side of the debate, we wonder how it affects the micro level. is it possible to live on the income of airbnb? Are there hosts that exercise it professionally?



## Summary of Findings


- Airbnb's business model focuses on entires homes and private rooms
- The price curve is completely right skewed. The majority of their prices are between € 50 100 per night.
- Prices linetime: there is a seasonality in the variation of prices, weekends have an average higher value and public events such as sonnar or mobile world congress coincide with a rise in prices.
- The neighborhoods with the most expensive price per night are Eixample and Sarria.
Sarria is a traditional neighborhood of the city with a residential character that mostly houses houses with high purchasing power. The Eixample is the most typical neighborhood in Barcelona that transmits the true experience of visiting the city and this can be seen reflected in the number of reviews in this neighborhood, more than 50% of the total.
- Hosts with more than 100 listings under their control exert a very strong pressure on the rental housing market, and on average their prices are 10% higher. Obviously, micro-businesses have emerged around this platform that has very attractive results.
