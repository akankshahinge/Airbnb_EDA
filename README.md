# Airbnb_EDA
Data analysis(EDA) for Airbnb-NewYork dataset

* Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings.
* Libraries like Pandas, Numpy, Matplotlib, Seabornfor cleaning, visualization, and analysis.

#### Dataset
The dataset contains 20,765 entries and 22 features, including:

 - id: Unique identifier for each listing
- name: Title of the Airbnb listing
- host_name: Name of the host
- neighborhood_group: Group (borough) where the listing is located
- latitude/longitude: Geolocation of listings
- price: Nightly rental price
- room_type: Type of accommodation (e.g., entire home, private room)
- reviews_per_month: Average monthly reviews for the listing
- availability_365: Number of available days in the year

## Exploratory Data Analysis (EDA)

### Univariate Analysis

* **Price Distribution:** A boxplot and a histogram were created to visualize the distribution of prices, revealing outliers and the overall price range.  Outliers above 1500 were removed for a clearer price distribution.  The histogram shows the frequency of different price ranges.
* **Availability Distribution:**  A histogram illustrates the distribution of listing availabilities throughout the year.

### Bivariate Analysis

* **Average Price by Neighbourhood Group:** Analyzed the average price of listings across different neighbourhood groups.
* **Price per Bed:** Calculated the average price per bed for each neighborhood group, providing insights into value per bed.
* **Price Dependency on Neighbourhood and Room Type:** A barplot visualizes how prices vary across different neighborhoods and room types.
* **Price vs. Number of Reviews:** A scatter plot explores the relationship between price and the number of reviews, colored by neighborhood group, revealing potential correlations.

### Multivariate Analysis

* **Pair Plot:** A pair plot showcases the pairwise relationships between key variables (price, minimum nights, number of reviews, reviews per month, availability) colored by room type. This helps visualize correlations and potential interactions.

### Geographical Distribution

* **Airbnb Listing Locations:** A scatter plot displays the geographical distribution of Airbnb listings on a map. This helps visualize listing density in different areas.

### Correlation Analysis

* **Heatmap:** A heatmap illustrates the correlation matrix for several key numerical features, providing a visual representation of the relationships between these variables (latitude, longitude, price, minimum nights, number of reviews, reviews per month, availability_365, and beds).


## Insights and Observations

*(Add specific observations you drew from the graphs here. For example:)*

*  High-priced listings appear to be concentrated in specific neighborhoods.
*  The number of reviews does not seem to have a strong positive correlation with price, suggesting other factors could be more influential.
*  Certain room types are prevalent in specific areas.
*  Understanding correlations through the heatmap might suggest further data analysis around which variables have a major impact on pricing.


## Further Exploration

*(Suggest potential next steps, like additional visualizations, advanced analysis methods or more in-depth exploration into specific insights)*

* Model building (predicting price, occupancy, etc.).
* Time series analysis of pricing and availability.
* Deeper dive into specific neighborhoods or room types.
