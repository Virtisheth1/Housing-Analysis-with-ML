# Housing-Analysis-with-ML

The goal of this project is to explore the relationship between various factors (e.g., living area, location) and housing prices, and to make data-driven conclusions that can inform buyers, sellers, or investors in the King County housing market.

1. Data Selection and Summary Statistics
- **Dataset**: The project uses a dataset containing housing data from King County.
- **Initial Exploration**: The dataset is filtered and summarized to understand the basic properties of the data, such as:
  - Average house price by zipcode.
  - Overall distribution of prices and house areas.

2. Filtering Data
- Applied filters to focus on specific areas of interest (e.g., certain zip codes, price ranges).
- Performed data cleansing to remove anomalies and ensure clean, reliable analysis.

3. Visualizations
- Visualized the correlation between **house sales price** and **area (sqft living)**, showing a positive correlation: as the living area increases, the sales price tends to increase.
- Created additional plots to explore relationships between housing prices and other variables like **number of bedrooms**, **bathrooms**, and **zipcode**.

## Technologies Used
- **Languages**: Python
- **Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for data visualization.
  - `scikit-learn` for potential future analysis and predictive modeling.

## Key Findings
- The **zip code** with the highest average house price is identified, providing insights into premium areas.
- A clear positive correlation between living area and sales price suggests that larger homes tend to sell for higher prices.
- Further analysis could involve building predictive models to forecast housing prices based on features like area, location, and number of bedrooms.
