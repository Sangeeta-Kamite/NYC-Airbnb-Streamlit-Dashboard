# NYC Airbnb Streamlit Dashboard
An interactive, customizable Streamlit dashboard for exploring and analyzing Airbnb listings in New York City. This project empowers users to visualize trends, perform market segmentation with clustering, and estimate listing prices using machine learning.

**Project Aim**

This project aims to develop a powerful yet intuitive data application that delivers actionable insights into New York City Airbnb listings. It combines exploratory analysis, clustering, and predictive modeling in one streamlined interface.
This dashboard can help:
- Airbnb hosts benchmark their listings.
- Travelers understand pricing and location trends.
- Data analysts and students practice geospatial and ML techniques.

**Features**
1. Explore Data
   - Search by host name or filter by neighborhood group.
   - Display selected columns of interest.
   - Quickly inspect raw listing-level data.
3. Visualizations
   - Heatmap of listings using latitude/longitude.
   - Time trend showing review activity over time.
   - Top 10 listings by price.
4. Clustering
   - Apply K-Means clustering to categorize listings by location and price.
   - Visualize clusters on an interactive map.
   - View cluster-wise summary of price stats.
5. Price Prediction
   - Estimate listing price using a Random Forest Regressor.
   - Input room type, nights, reviews, and availability to predict price.
6. Neighborhood Insights
   - View average prices by neighborhood group.
   - Analyze room type frequency and price distributions.
   - Filter listings by group and room type.

**Technologies Used**
- Python
- Streamlit – Web framework
- Pandas – Data manipulation
- Seaborn & Matplotlib – Visualization
- Plotly & PyDeck – Interactive maps and graphs
- Scikit-learn – ML models (KMeans, RandomForest)
- Base64 & CSS – Custom dashboard styling

**Use Cases**
User and Benefits
- Hosts: Competitive price insights and performance benchmarking
- Travelers: identify affordable neighborhoods and the best options
- Analysts: Segment the market, visualize distribution, and extract trends
- Students: Real-world project in ML + visualization + web app
- Planners:	Track tourism density across boroughs
