# Self-Assessment

## Overview of the Project

There has been conversation on social media and in the news about AirBNB as of late. Airbnb has hosted across the world and is continuing grow quickly since it founding, it made a great connection between property owners and travellers.

People who has vacant spaces can list on Airbnb, and guests can look for affordable and desired housing options.

By analyzing the listings in Now York city,  it seems that price is based on a number of factors, like locations, bedrooms, properly type and more.!

We were trying to find out does location and amenities make a listing more competitive? And how competitive it can be?

In order to set up a fair price to pay or charge for a listing, we built a model to predict the optimal price for a property based on its features.

## Team Member task:

- David: Gathered datasets and data cleaning of calendar data, database set up; 
- Tope: City Zip Code Clustering; 
- Lynette: Data Cleaning of listings data; Tableau Vitualization
- Orange Xin Lan: Data Cleaning of listings data; Touch up on Tablleau Visstualization
- Daniella: Created repository, contributed to ReadMe and  did Machine Learning file. 

## Individual Task

My main task was focusing on Data cleaning.
- Both data sets were cleaned using Python pandas library in Jupyter Notebook and exported to PostgreSQL using SQLAlchemy.
- Data was stored and shared among the team on the AWS RDS service.

  
## Communications Protocol  

There are three different Time Zones according us, it is not that easy for us to get online at the same time. But all of us compromised, we met up through Zoom, shared out ideas and progress.
Our group maintains communication through Slack, Zoom, Class Breakout rooms, and shares our work and ideas via Github through our shared repository.

## Machine Learning Model

  1. To predict Airbnb list prices for NY metro areas
  2. Encode categorical variables
  3. Started with 39,000 rows of data; cleaned to 28,010
  4. Utilized 3 different machine learning algorithms:
      - Linear Regression Model
      - Random Forest Regressor Model
      - Decision Tree Regressor Model
      
## Results
![this is an image](https://github.com/Orangexinlan/Self-Assessment/blob/b5a5a84ac65706f819a6a288cec85372d06d56da/Results.png)
  
## Conclusion

- After assessing and analyzing the three algorithms;
- We decided to use RMSE (root mean squared error) to determine which algorithm is the best predictor of Airbnb list price
- The lower the RMSE, the better for predictor analysis
- Our analysis concluded that the Random Forest Regressor is the best price predictor among the algorithm used for MY metro Airbnb price.
