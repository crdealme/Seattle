# Analyzing the Seattle AirBnB Data

Table of Contents
1. The libraries I have used
2. Project Motivation
3. File descriptions
4. Summary of the results
5. Acknowledgements

1. The libraries I have used
- numpy 
- pandas
- matplotlib.pyplot 
- missingno 

2. Project Motivation
The project motivation aims to answer the following questions (using the CRISP-DM Process):
1. What are the busiest times of the year to visit Seattle?
2. Do the holydays influence the AirBnB availability?
3. What is the relationship between prices and availability?
4. Does the review variables influence price?

3. File descriptions
The used data is public and available in: (https://www.kaggle.com/airbnb/seattle)
The dataset basically contains the information:
- calendar.csv: calendar availability of listings and price
- listings.csv: information about all the available listings
- reviews.csv: listing reviews by the users

4. Summary of the results
- The busiest times of the year to visit Seattle are the beginning of January, April and July;
- Independence Day indicates a great level of unavailability. The other holidays don't seem to highly influence occupancy;
- The data suggests that the prices increase as we have more AirBnB availability. However, this is not a perfect correlation. The Spearman correlation metric indicates a correlation of 0.41 between availability and prices;
- Each review variable is poorly correlated with price. Based on data, we can't say that the review metrics influence prices.

5. Acknowledgements
My acknowledgements to Kaggle and Udacity Course.
