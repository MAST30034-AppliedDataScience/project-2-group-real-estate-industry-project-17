# Group 17 Real Estate Consulting Project

## Overview
This project aims to predict property rents for the next three years and identify key features influencing these rents. Our analysis will provide insights and recommendations based on the forecasted data.

## Group Members:
- Luochan Bao (1131378)
- Xiaowei Guo (1346452)
- Hao Tian (1342982)
- Hanyang Shi (1346903)
- Zixuan Zhang (1132592)


## Research Objective:
The main objective is to predict property rents and analyze the key factors that influence them. The recommendations will be made based on these predictions and insights.

## Project Timeline:
- The data analyzed and predictions are based on the timeline of 2023.

## Pipeline Instructions

### Notebooks Execution:
To run the pipeline, please navigate to the `notebooks` directory and execute the following Jupyter notebooks in order:

 1. **population_EDA.ipynb**: Perform exploratory data analysis (EDA) on demographic data.
 
 2. **EDA_aff.ipynb**: Conduct EDA on economic prosperity data.
 
 3. **avg_rent.ipynb**: Analyze and calculate the average rent prices in each area.
 
 4. **code_predict.ipynb**: Analyze feature importance using regression models and evaluate the model performance.
 
 5. **code_sa2postcode.ipynb**: Convert SA2 area codes to zip codes for finer geographic analysis.
 
 6. **code_top10_new.ipynb**: Visualize the top ten suburbs with the highest growth rates and make predictions for the next three years.
 
 7. **distance_facilities.ipynb**: Calculate the distance of properties from amenities (e.g., schools, stores) to assess location convenience.
 
 8. **distance_train_station.ipynb**: Calculate the distance from properties to the nearest train station for accessibility analysis.
 
 9. **Feature_interested.ipynb**: Select and engineer features for optimizing model performance.
 
 10. **growth rate and price.ipynb**: Analyze and visualize the relationship between growth rates and rent prices. Use Random Forest and Gradient Boost models to predict the top ten highest-rent suburbs.
 
 11. **map_growrate.ipynb**: Generate map visualizations showing growth rates across different regions.
 
 12. **map_top10.ipynb**: Create geographic visualizations of the top 10 suburbs with the highest predicted growth rates.
 
 13. **radar_code.ipynb**: Visualize various influences on affordability and livability using radar charts.

### Additional Files:
- **scrape.py** (in the `scripts` directory): Use this script to start scraping the data needed for analysis.
