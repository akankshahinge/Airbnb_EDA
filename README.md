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

1. Price Trends:
   Manhattan has the most expensive listings, followed by Brooklyn.
   Entire homes/apartments cost significantly more than private or shared rooms.
2. Room Type Distribution:
   Entire homes/apartments are the most common, but private rooms offer budget-friendly options.
3. Outliers in Price:
   Few listings priced at $10,000+ were detected, indicating the need to filter such extreme values.
4. Availability Patterns:
   Listings with high availability tend to have lower prices and more reviews, likely due to better guest experience.
5. Host Behavior:
   Some hosts manage multiple listings, indicating a trend toward professional hosting.


## Further Exploration

* Model building (predicting price, occupancy, etc.).
* Time series analysis of pricing and availability.
* Deeper dive into specific neighborhoods or room types.
