# LP3-Time-Series-Analysis
This is a time series project that seeks to predict sales of the Favourita company.
## Summary
| Code          |     Name                       | Published Article|    PowerBi Dashboard
| ------------- | -------------                  | -------------    |    -----------------
| LP3           | LP3-Time Series Analysis |  [Article](https://medium.com/@aaronayitey/sales-forecasting-using-time-series-regression-a6671a371712)               |[PowerBI](https://bit.ly/team_jackson_hole)

## Description
Favorita stores hold a significant presence in the Ecuadorian grocery retail market and are renowned for providing a wide range of products to customers across the country. With a customer-centric approach and a focus on continuous improvement, Favorita stores are dedicated to delivering value to their customers and building lasting relationships. By leveraging advanced data analytics and forecasting models, Favorita aims to optimize its inventory management, ensure product availability, and enhance the overall shopping experience.

## Objective
To develop a predictive model for store sales for Corporation Favorita, a large grocery retailer headquartered in Ecuador. The model aims to predict the unit sales of numerous items across various Favorita stores, enabling more precise estimation of sales performance.

## Data Understanding
For the Store Sales Time Series Forecasting project, we have several datasets available:

* `train.csv`: This dataset contains historical sales data, including store numbers, product families, onpromotion information, and the target variable ‘sales,’ representing the total sales for each product family at a specific store on a given date.
* `test.csv` : Similar to the train dataset, this file contains the same features as the training data but does not include the ‘sales’ column. Our goal is to predict sales for the test data based on the trained model.
* `transaction.csv`: This dataset provides information about transactions made on specific dates at different stores.
* `stores.csv` : Store metadata, including city, state, type, and cluster information.
* `oil.csv`: Daily oil prices, which include values during both the train and test data timeframes.
* `holidays_events` .csv: Contains information about holidays and events, including metadata about transferred and bridge holidays.

  **From thoroughly examining the dataset, we came out with the following analytical questions:**
1. Is the train dataset complete (has all the required dates)?
2.  Which dates have the lowest and highest sales for each year?
3. Did the earthquake impact sales?
4. Are certain groups of stores selling more products? (Cluster, city, state, type)
5. What is the relationship between oil prices and store sales? 
6.  Do holidays and events influence store sales? Are there specific holidays/events that drive higher sales?
7. Is there a significant difference in sales by location and by store type?
8. Which store has the highest average sales, and which one has the lowest?

## Summary and Findings


## Modelling
