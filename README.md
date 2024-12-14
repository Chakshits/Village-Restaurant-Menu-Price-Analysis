# Village-Restaurant-Menu-Price-Analysis
Village Restaurant Menu Price Analysis

This Python script analyzes restaurant menus, scrapes price data, and predicts potential price adjustments based on external factors like weather conditions and estimated demand.
**Key Features:**
● Menu Scraping: Extracts menu items and prices from a specified Yelp page using web scraping techniques (BeautifulSoup library).
● Weather Integration: Fetches real-time weather data using the OpenWeatherMap API to incorporate weather conditions into price predictions.
● Dynamic Pricing Logic: Implements a price prediction model that increases prices under specific conditions:
○ Temperature below 45°F (7.2°C)
○ Presence of snow, rain, or storms
○ High demand (simulated with a "busy" flag)
● Clear Output: Presents the analysis results with original prices, predicted prices, and indications of price changes.

**Classes:**
●MenuItem: A data class representing a menu item with its name, original price, and a predicted price.
●APIManager: Handles API interactions, including:
○Retrieving weather data from OpenWeatherMap
○Scraping menu details from Yelp
●PricePredictionEngine: Contains the logic to predict price adjustments based on weather and demand.
●RestaurantAnalyzer: Orchestrates the entire analysis process, fetching data, predicting prices, and displaying results.

**How to Use:**
1.Set up API keys: Replace placeholder API keys for Yelp and OpenWeatherMap with valid keys.
2.Run the script: Execute the main function. The script will fetch data, perform analysis, and display the results.
Potential Enhancements:
● More Sophisticated Pricing Model: Incorporate additional factors (e.g., time of day, day of the week, historical sales data) for more accurate predictions.
● Machine Learning Integration: Train a machine learning model to predict prices based on a larger dataset.
● User Interface: Create a user-friendly interface for inputting restaurant details and viewing results.

This project demonstrates a practical application of web scraping, API integration, and data analysis for a real-world business scenario.
