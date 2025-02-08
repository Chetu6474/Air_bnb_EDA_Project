![Description](https://github.com/Chetu6474/Air_bnb_EDA_Project/blob/main/Airbnb.png)
# Air bnb EDA Project

##📖 Project Overview
This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like Pandas, Numpy, Matplotlib, and Seaborn for data cleaning, visualization, and analysis.

##📌 Objective
The goal of this project is to:
- Analyze room types, prices, and availability across different neighborhoods.
- Understand host behavior and listing patterns.
- Detect potential outliers in prices.
- Provide recommendations for guests and hosts based on insights.

##📊 Dataset
The dataset contains 20,765 entries and 22 features, including:
- `id`: Unique identifier for each listing
- `name`: Title of the Airbnb listing
- `host_name`: Name of the host
- `neighbourhood_group`: Borough where the listing is located
- `latitude/longitude`: Geolocation of listings
- `price`: Nightly rental price
- `room_type`: Type of accommodation (e.g., entire home, private room)
- `reviews_per_month`: Average monthly reviews for the listing
- `availability_365`: Number of available days in the year

##🛠 Workflow
###📜 Data Cleaning
- Handled missing data in `price`, `neighbourhood_group`, and `room_type` columns.
- Converted `last_review` to a datetime object.
- Capped listings with prices > $1,000 to avoid skewed visualizations.

###📜 Exploratory Data Analysis (EDA)
- **Room Type Distribution**: Used bar plots to show that entire homes/apartments are the most common.
- **Neighborhood Price Analysis**: Boxplots revealed Manhattan has the highest average prices.
- **Availability Trends**: Heatmaps demonstrated the correlation between price, availability, and reviews.
- **Price Outliers**: Histograms showed that most listings fall in the $50-$300 range.
- **Host Behavior**: Boxplots analyzed hosts with multiple listings.

###📜 Data Visualization
- **Pairplot**: Correlations among price, availability, and number of reviews.
- **Heatmap**: Feature correlation visualization.
- **Histograms & Boxplots**: Price outlier detection.
- **Bar Charts**: Room type and neighborhood group distributions.

##🎯 Key Insights
- **Manhattan has the most expensive listings, followed by Brooklyn.**
- **Entire homes/apartments are the most common but private rooms offer budget-friendly options.**
- **Some hosts manage multiple listings, suggesting professional hosting.**
- **Listings with high availability often have more reviews and lower prices.**

##🐍 Technologies Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**
