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

#### EDA (Exploratory Data Analysis)
1. Room type distribution:

Visualized the count of each room type using bar plots.
Identified Entire home/apt as the most common room type.
Neighborhood group insights:

2. Analyzed price variations by boroughs.
Manhattan had the highest average prices.
Availability trends:

3. Used heatmaps to show correlations among price, availability_365, number_of_reviews, and beds.
Price distribution:

Used histograms to show the distribution of prices.
Majority of the listings were priced between $50 - $300.
4. Host listings:

5. Analyzed hosts with multiple listings using boxplots to identify key contributors.
Review behavior:

Used pair plots to show relationships between number of reviews, price, and availability.
