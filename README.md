# Airbnb NYC Exploratory Data Analysis (EDA)  

## Project Overview  
This project conducts an exploratory data analysis of Airbnb listings in New York City using the dataset `Airbnb NYC 2019.csv`. The dataset contains detailed information about 22,059 listings and includes attributes such as neighborhood, room type, pricing, availability, and host details. The analysis focuses on uncovering trends, patterns, and insights to better understand the dynamics of Airbnb's presence in NYC.  

## Dataset Information  
- **Dataset Name:** Airbnb NYC 2019.csv  
- **Total Entries:** 22,059  
- **Total Columns:** 16  

| Column Name                       | Non-Null Count | Data Type | Description                                       |
|-----------------------------------|----------------|-----------|---------------------------------------------------|
| `id`                              | 22,059         | int64     | Unique identifier for each listing.              |
| `name`                            | 22,044         | object    | Name of the listing.                             |
| `host_id`                         | 22,059         | int64     | Unique identifier for the host.                  |
| `host_name`                       | 22,045         | object    | Name of the host.                                |
| `neighbourhood_group`             | 22,059         | object    | Borough of NYC where the listing is located.     |
| `neighbourhood`                   | 22,059         | object    | Specific neighborhood of the listing.            |
| `latitude`                        | 22,059         | float64   | Latitude of the listing's location.              |
| `longitude`                       | 22,059         | float64   | Longitude of the listing's location.             |
| `room_type`                       | 22,058         | object    | Type of the room (e.g., Entire home, Private).   |
| `price`                           | 22,058         | float64   | Price per night for the listing.                 |
| `minimum_nights`                  | 22,058         | float64   | Minimum number of nights required for booking.   |
| `number_of_reviews`               | 22,058         | float64   | Total number of reviews for the listing.         |
| `last_review`                     | 18,358         | object    | Date of the last review.                         |
| `reviews_per_month`               | 18,358         | float64   | Average number of reviews per month.             |
| `calculated_host_listings_count`  | 22,058         | float64   | Number of listings per host.                     |
| `availability_365`                | 22,058         | float64   | Number of days available for booking in a year.  |

## Project Objectives  
1. Clean and preprocess the dataset to address missing values, outliers, and inconsistencies.  
2. Perform an in-depth analysis of neighborhoods, room types, pricing, and availability.  
3. Use data visualization techniques to uncover patterns and trends in the dataset.  
4. Derive actionable insights that benefit stakeholders, such as hosts and guests.

## Key Tools and Libraries  
- **Programming Language:** Python  
- **Libraries Used:** pandas, matplotlib, seaborn, numpy  

## Deliverables  
- Summary statistics and data cleaning details.  
- Visualizations to represent pricing trends, availability, and neighborhood distribution.  
- Insights and recommendations based on the analysis.  

## How to Use  
1. Clone this repository and download the dataset `Airbnb NYC 2019.csv`.  
2. Open the Jupyter Notebook file and run the cells step by step.  
3. Visualizations and insights will be generated as outputs in the notebook.  

## License  
This project is for educational and analytical purposes only. The dataset is publicly available and belongs to its respective owner.  
