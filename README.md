# Personalized-Airbnb-Investment-Evaluator
**Introduction:**

With the resurgence of global travel, the demand for short-term rental accommodations like Airbnb has risen significantly, especially in high-tourism cities such as New York City (NYC). This project aimed to assist potential Airbnb investors in identifying profitable neighborhoods, understanding market trends, optimizing pricing strategies, and minimizing risks. By integrating Airbnb listings data and NYC housing market information, we created a comprehensive interactive dashboard to provide actionable insights for property investment.

**Objective:**

The goal of this project was to analyze the NYC Airbnb market to help investors:

1. Identify high-demand and high-return neighborhoods.
2. Develop optimal pricing strategies based on local market dynamics.
3. Minimize risks by assessing market competition and fluctuating property values.

**Dataset and Sources:**

1. **Airbnb Listings Data (2019)**: Contains detailed information about Airbnb properties, including room types, prices, and number of reviews, sourced from Kaggle.
2. **NYC Housing Market Data (2019)**: Includes property prices and neighborhood details, also sourced from Kaggle.

**Methodology:**

1. **Data Cleaning and Integration**: Combined datasets to align Airbnb listings with corresponding property prices, ensuring consistency and completeness.
2. **ROI Calculation**:
    - **Formula**: ROI = Revenue / Cost
    - Revenue was approximated using `minimum stay × reviews × price per night`, serving as a proxy for occupancy rate due to dataset limitations. Cost was based on average property prices.
3. **Geospatial and Trend Analysis**:
    - Mapped ROI across NYC neighborhoods to visualize investment hotspots.
    - Identified trends in minimum stay requirements and room types to inform investment strategies.
4. **Risk Assessment**: Evaluated the percentage of unpopular listings (low reviews) and analyzed borough-specific property value trends to highlight areas of higher stability or volatility.

**Key Findings:**

1. **High ROI Areas**: Staten Island and the Bronx emerged as top locations for Airbnb investment, offering strong returns due to low property costs and steady demand.
2. **Riskier Markets**: Manhattan, despite its popularity, showed high risks due to property price declines and market saturation.
3. **Market Trends**:
    - Long-term rentals performed better in areas like Greenpoint.
    - Short-term stays were more successful in neighborhoods such as the Financial District.
4. **Room Types**: Entire homes dominated the market in Manhattan and Brooklyn, while private rooms were more competitive in other boroughs.

**Recommendations:**

1. Focus on neighborhoods with stable or growing property values, such as Staten Island and Queens, for long-term investments.
2. Use dynamic pricing strategies to adapt to seasonal and location-specific demand.
3. Optimize room types and rental durations to align with neighborhood preferences, catering to long-term stays in some areas and short-term in others.

**Conclusion:**

The Personalized Airbnb Investment Evaluator equips investors with data-driven insights to navigate the competitive NYC Airbnb market. By leveraging ROI modeling, market trends, and risk assessments, this project demonstrates the power of data analytics in making informed investment decisions.
