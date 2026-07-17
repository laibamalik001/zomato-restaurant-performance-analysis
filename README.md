# zomato-restaurant-performance-analysis
End-to-end analysis of Zomato restaurant data (123K+ records across 17 Indian cities) with an interactive Power BI dashboard covering pricing trends, cuisine performance, ratings distribution, and top restaurants.
This project analyzes restaurant and menu-item level data scraped from Zomato, covering over 123,000 records across 17 major Indian cities such as Mumbai, Bangalore, Delhi, and Hyderabad. The dataset includes ratings (dining & delivery), votes, pricing, cuisine types, and engineered features like restaurant popularity, price-per-vote, and bestseller flags. An interactive Power BI dashboard visualizes average price by city, cuisine-wise ratings, rating distributions, and top-performing restaurants like McDonald's, Burger King, and Domino's Pizza enabling quick insights into pricing trends and customer satisfaction across regions and cuisines.

Dataset
File: enhanced_zomato_dataset_clean.csv — 123,657 records, 826 restaurants, 48 cuisines, 17 cities (Mumbai, Bangalore, Hyderabad, Delhi, Chennai, Pune, and more). Columns include restaurant name, city, cuisine, dining/delivery ratings, votes, prices, and engineered features like popularity score and bestseller flags.

Dashboard
Built in Power BI, the dashboard includes: average price by city, cuisine-wise rating and count breakdown, rating distribution across restaurants, top restaurants by rating volume (McDonald's, Burger King, Domino's, etc.), and interactive filters for City and Cuisine.

Tools Used
Python (Pandas) for data cleaning and feature engineering, Power BI for dashboard and visualization.

Files
enhanced_zomato_dataset_clean.csv (cleaned dataset), zomato_dashboard.pbix (Power BI file, if included), README.md (project overview).

Key Insights
Pricing varies significantly by city, with metro cities like Mumbai on the higher end. Beverages, Pizza, and Fast Food are the most common and highest-rated cuisines. Most restaurants cluster around a 3.5–4.0 rating. Large chains (McDonald's, Burger King, Domino's) lead in customer engagement and votes.

