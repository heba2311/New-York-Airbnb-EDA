# New-York-Airbnb-EDA
This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like Pandas, Numpy, Matplotlib, Seabornfor cleaning, visualization, and analysis.

# 1. Data Cleaning
Handle missing data: price, neighborhood, and beds columns had null values.
Fix data types: Converted last_review to a datetime object.
Remove outliers: Listings with prices > $1,000 were capped to avoid skewed visualizations.
# 2. EDA (Exploratory Data Analysis)
Room type distribution:

Visualized the count of each room type using bar plots.
Identified Entire home/apt as the most common room type.
Neighborhood group insights:

Analyzed price variations by boroughs.
Manhattan had the highest average prices.
Availability trends:

Used heatmaps to show correlations among price, availability_365, number_of_reviews, and beds.
Price distribution:

Used histograms to show the distribution of prices.
Majority of the listings were priced between $50 - $300.
Host listings:

Analyzed hosts with multiple listings using boxplots to identify key contributors.
Review behavior:

Used pair plots to show relationships between number of reviews, price, and availability.
# 3. Data Visualization
Pairplot: To see correlations among price, availability, and number of reviews.
Heatmap: Showing correlations among numerical features.
Histograms and Boxplots: To detect outliers in price.
Bar Charts: Displaying room types and neighborhood group distributions.
