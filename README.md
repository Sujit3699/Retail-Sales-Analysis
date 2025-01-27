# Retail Sales Analysis  

## Overview  
This project analyzes retail sales data to uncover key insights into sales trends, customer behavior, and the impact of external factors like weather and holidays. The goal is to help **RetailPulse**, a retail analytics company, optimize sales performance, improve customer engagement, and make data-driven decisions to enhance overall efficiency.  

---

## Problem Definition  
RetailPulse aims to optimize sales and engagement across its stores but faces challenges in:  
- Understanding the key drivers of sales.  
- Analyzing customer behavior across demographics and regions.  
- Assessing the impact of external factors such as weather and holidays.  

This analysis addresses these challenges by providing actionable insights to drive revenue growth, improve product placements, and enhance operational efficiency.  

---

## Objectives  
1. **Understand Sales Drivers**: Analyze the influence of pricing, promotions, product categories, and external factors on sales.  
2. **Customer Behavior Analysis**: Segment customers based on demographics and purchasing patterns to uncover regional and behavioral trends.  
3. **Evaluate External Factors**: Assess how weather and holidays impact sales and recommend strategies to optimize performance during these periods.  

---

## Datasets  
The project utilizes three datasets sourced from Kaggle, each providing essential information for the analysis:  

1. **Sales Data**  
   - **Description**: Transaction-level data including sales dates, product categories, and transaction amounts.  
   - **Key Columns**: `Date`, `Product Category`, `Price per Unit`, `Quantity`, `Total Amount`.  
   - **Dataset Link**: [Retail Sales Dataset](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)  

2. **Customer Data**  
   - **Description**: Demographic and behavioral data for customers.  
   - **Key Columns**: `Customer ID`, `Age`, `Gender`, `Location`, `Frequency of Purchases`.  
   - **Dataset Link**: [Customer Shopping Trends](https://www.kaggle.com/datasets/bhadramohit/customer-shopping-latest-trends-dataset)  

3. **Store Data**  
   - **Description**: Operational data for stores, including weather and seasonality information.  
   - **Key Columns**: `Store ID`, `Weather Condition`, `Seasonality`, `Category`.  
   - **Dataset Link**: [Retail Store Inventory Forecasting](https://www.kaggle.com/datasets/anirudhchauhan/retail-store-inventory-forecasting-dataset)  

---

## Key Features of the Analysis  
### 1. **Sales Trends**  
   - Electronics sales peaked in May and dipped in October and December.  
   - Clothing sales dropped in July, indicating a need for mid-year promotions.  
   - Beauty products spiked in July and October, suggesting key months for targeted campaigns.  

### 2. **Customer Insights**  
   - Age groups 18–30 and 41–50 represent the most engaged customers.  
   - The <18 age group is an untapped segment for tailored marketing efforts.  

### 3. **Location Performance**  
   - High-performing states include Delaware and New York, with sales exceeding $300,000.  
   - Underperforming regions like Kansas and New Jersey require localized marketing strategies.  

### 4. **Impact of External Factors**  
   - Sales increase during snowy and rainy weather.  
   - Holiday sales are three times higher than non-holiday periods, emphasizing the importance of timely promotions.  

---

## Tableau Dashboard  
Explore the interactive dashboard that visualizes all key findings:  
[Retail Sales Analysis Dashboard](https://public.tableau.com/views/RetailSalesAnalysisDashboard_17379234251960/RetailSalesAnalysis)  

---

## Challenges Faced  
- **Data Integration**: Standardized Customer IDs and season names to ensure accurate merging of datasets.  
- **Limited Geographic Data**: Relied on city-level aggregation due to the absence of latitude and longitude.  
- **API Limitations**: Weather data integration was constrained by API request caps.  
- **Data Alignment**: External datasets like holidays required manual alignment with sales data.  

---

## Recommendations  
1. Launch promotions for Electronics in May and target slow months like March and December.  
2. Offer mid-year discounts for Clothing during July to counter seasonal slumps.  
3. Focus marketing efforts on the 18–30 and 41–50 age groups using tailored campaigns.  
4. Improve sales in underperforming regions with localized promotions and product adjustments.  
5. Maximize holiday sales by preparing exclusive deals and bundles well in advance.  
6. Promote indoor-related products during adverse weather conditions.  

---

## Technologies Used  
- **Python**: Data cleaning, transformation, and analysis.  
- **Tableau**: Data visualization and dashboard creation.  
- **Kaggle Datasets**: Source of raw data for analysis.  

---

## How to Use This Repository  
1. Clone this repository to your local machine:  
   ```bash
   git clone <repository-url>
