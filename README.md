# Housing Price Analysis in the Reno–Tahoe Area

## 1. Overview
The purpose of this project is to analyze and report on the current state of the housing market in the Reno-Tahoe area, which includes Washoe County, Douglas County, and the city of Carson in Northern Nevada. This analysis will be particularly useful for prospective investors and homebuyers new to the area, providing them with a clear understanding of the local market dynamics.

- **Dataset**:

The primary dataset was extracted from public real estate websites, such as Zillow and Realtor, encompassing over 26,000 real estate transactions spanning the last 7 years. It includes parameters such as sold price, date of sale, square footage, location and property features (e.g., number of bedrooms and bathrooms). 

- **Questions to Address**:
 
The main questions I seek to answer are:

* How have housing prices changed over time?
* Which factors have the greatest impact on housing prices?

As well as obtaining other metrics to help the reader better understand the state of the local market. 

---

## 2. Data Cleaning and Preprocessing

### Data Cleaning
- Fixed typos in city names.
- Removed cities outside the study area. 
- Deleted irrelevant columns (e.g., agent contact numbers).
- Excluded records with missing critical data (e.g., sold price, square footage).

### Data Preprocessing
- Standardized date formats.
- Created and calculated new variables (e.g., price per square foot, total number of bathrooms).
- Encoded categorical variables for analysis.

---

## 3. Analysis

### Exploratory Data Analysis (EDA)
- Analyzed price distributions and identified outliers.
- Explored correlations between price, square footage, and location.
- Analyzed quarterly trends in housing prices.
- Examined market fluctuations based on location and property features.

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
  - Median housing prices vary greatly by location, with Incline Village, Glenbrook and Zephyr Cove leading and Carson City, Sun Valley and Gardnerville lagging.  
  - Key determinants of housing prices include square footage, year built, and city.

- **Limitations**:  
  - The dataset spans only 7 years of data. A longer dataset (e.g., 15 years) would provide a more comprehensive view of long-term trends and help account for broader market cycles, such as the effects of economic recessions or booms.

- **Future Directions**:  
  - Explore the impact of additional variables such as school districts or proximity to amenities.  
