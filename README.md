# Housing Price Analysis in the Reno–Tahoe Area

## 1. Introduction and Overview
- **Project Objective**:  
  This project analyzes over 26,000 real estate transactions in Washoe County to uncover trends and key factors influencing the local housing market.  
- **Dataset Information**:  
  The dataset includes parameters such as sold price, date of sale, square footage, location, and property features (e.g., number of bedrooms and bathrooms).  
- **Questions to Address**:  
  - How have housing prices changed over time?  
  - What are the key metrics (e.g., median, mean, mode, minimum, and maximum prices) for different cities?  
  - Which parameters most influence housing prices?  
- **Tools and Methods**:
  - Microsoft Excel was used for the cleaning of the dataset.
  - Python was used for data analysis, including trend identification and predictive modeling.
  - Tableau dashboards to present findings.

---

## 2. Data Exploration and Preprocessing

### Data Cleaning
- Fixed typos in city names.
- Removed cities outside Washoe County.
- Deleted irrelevant columns (e.g., agent contact numbers).
- Excluded records with missing critical data (e.g., sold price, square footage).

### Data Transformation
- Standardized date formats.
- Created new variables (e.g., price per square foot).
- Encoded categorical variables for analysis.

### Exploratory Data Analysis (EDA)
- Analyzed price distributions and identified outliers.
- Explored correlations between price, square footage, and location.


---

## 3. Analysis and Insights

### Price Trends Over Time
- Prices show seasonal fluctuations but an overall upward trend over time.  
![quarterly_trends](https://github.com/user-attachments/assets/83feb46c-0bd2-4d51-8dc2-fabd3b93f6c1)

### Price Distributions
- Median housing prices vary significantly between cities:  
  - **Highest Median Prices**:  
    - Incline Village: $1,500,000  
    - Glenbrook: $1,490,000  
    - Zephyr Cove: $1,092,500  
  - **Lowest Median Prices**:  
    - Carson City: $376,000  
    - Sun Valley: $380,000  
    - Gardnerville: $445,000  
![distribution](https://github.com/user-attachments/assets/fcbddcb8-618b-4cc2-af4a-24729128fc7e)


### Factors Affecting Housing Prices
- Predictive modeling identified the following parameters as having the greatest impact on housing prices:  
  - **Square footage (sqft)**  
  - **Year built**  
  - **City**  
![feature_importance](https://github.com/user-attachments/assets/7f40b80a-5812-478b-b9f8-f24ab8737f85)

---

## 4. Tableau Dashboard
![Housing Price Analysis Dashboard](https://github.com/user-attachments/assets/19fefe97-6f01-42ce-9329-76a77a9bcbef)

---

## 5. Conclusion and Future Work
- **Summary of Findings**:  
  - Housing prices show seasonal changes but have increased over time.  
  - Median housing prices vary greatly by location, with Incline Village, Glenbrook, and Zephyr Cove leading, and Carson City, Sun Valley, and Gardnerville lagging.  
  - Key determinants of housing prices include square footage, year built, and city.

- **Limitations**:  
  - The dataset spans only 7 years of data. A longer dataset (e.g., 15 years) would provide a more comprehensive view of long-term trends and help account for broader market cycles, such as the effects of economic recessions or booms.

- **Future Directions**:  
  - Explore the impact of additional variables such as school districts or proximity to amenities.  
