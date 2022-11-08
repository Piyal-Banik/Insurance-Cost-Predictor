
## Insurance Cost Predictor

Create a Machine Learning model which predicts the charges of Insurance

  
## Acknowledgements

 - [Category:Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
 

## Author

- [@PiyalBanik](https://twitter.com/PiyalBanik)

  
## Business Understanding
The main goal of this project is to collect and analyze data in order predict the price of insurance. What are the factors that decide the price of an insurance? 


## Analytical Approach: 

Our target variable is Quantitative [take on continuous number], and hence we need regression models for this task.


## Data Requirements:

I needed a dataset that would have various characteristics of an insurance subscriber and the associated charges. 


## Data Collection:

- The dataset is taken from kaggle


## Data Understanding

- The Wikipedia page contains a list of suburbs in Melbourne. There are 212 suburbs in Melbourne which I extracted using a web scraping technique with the help of Python BeautifulSoup and Request packages.
- the geographical coordinates such as latitude and longitude of each suburb were collected using Python’s Geocoder package.
- Then, Foursquare API was used to extract details about the various venues present in each suburb.
- Once, the location data was extracted by using Geocoder, I used the Folium package to visualize the data on a map. This ensured us that the data we retrieved was correct. 
- Foursquare API was used to obtain the top 100 venues within a radius of 2000 meters.


## Modeling & Evaluation

Trained 
- Multiple Linear Regression and received r-squared value of 0.796 
- Polynomial Regression and received r-squared value of 0.884
- RandomForest Regressor and received r-squared value of 0.873
