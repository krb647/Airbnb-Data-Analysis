# New York Airbnb Data Analysis 

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on New York Airbnb data to uncover trends and patterns in rental listings. Libraries like **Pandas**, **Numpy**, **Matplotlib**, and **Seaborn** were used for data cleaning, visualization, and analysis.

## Objective
The goals of this project are to:

- Analyze room types, prices, and availability across different neighborhoods.
- Understand host behavior and listing patterns.
- Detect potential outliers in prices.
- Provide recommendations for guests and hosts based on insights.

## Dataset
The dataset includes **20,765 entries** with **22 features**, such as:

- **id**: Unique identifier for each listing
- **name**: Title of the Airbnb listing
- **host_name**: Name of the host
- **neighborhood_group**: Borough where the listing is located
- **latitude/longitude**: Geolocation of listings
- **price**: Nightly rental price
- **room_type**: Type of accommodation (e.g., entire home, private room)
- **reviews_per_month**: Average monthly reviews for the listing
- **availability_365**: Number of available days in the year

## Steps and Workflow

### 1. Data Cleaning
- **Handle missing data**: Addressed null values in price, neighborhood, and beds columns.
- **Fix data types**: Converted `last_review` to a datetime object.
- **Remove outliers**: Capped prices over $1,000 to avoid skewing visualizations.

### 2. Exploratory Data Analysis (EDA)
- **Room Type Distribution**:
  - Visualized the count of each room type using bar plots.
  - Found Entire home/apt to be the most common room type.

- **Neighborhood Group Insights**:
  - Analyzed price variations by boroughs.
  - Identified Manhattan as having the highest average prices.

- **Availability Trends**:
  - Used heatmaps to show correlations among price, availability, number of reviews, and beds.

- **Price Distribution**:
  - Created histograms to show price distribution.
  - Found that the majority of listings were priced between $50 - $300.

- **Host Listings**:
  - Analyzed hosts with multiple listings using boxplots to identify major contributors.

- **Review Behavior**:
  - Used pair plots to observe relationships between reviews, price, and availability.

### 3. Data Visualization
- **Pair Plot**: To explore correlations among price, availability, and reviews.
- **Heatmap**: To show correlations among numerical features.
- **Histograms and Boxplots**: To identify outliers in price.
- **Bar Charts**: To display distributions of room types and neighborhood groups.

## Key Findings and Insights## conclusion

- **Price Trends**:
  - Manhattan listings are the most expensive, followed by Brooklyn.
  - Entire homes/apartments cost significantly more than private or shared rooms.

- **Room Type Distribution**:
  - Entire homes/apartments are the most common; private rooms provide budget-friendly options.

- **Outliers in Price**:
  - Detected a few listings priced over $10,000, highlighting the need to filter extreme values.

- **Availability Patterns**:
  - Listings with high availability generally have lower prices and more reviews, likely due to positive guest experiences.

- **Host Behavior**:
  - Some hosts manage multiple listings, indicating a shift toward professional hosting.

## Conclusion
This project offers valuable insights into the New York Airbnb market, helping both guests and hosts make informed decisions. By using EDA techniques, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.

