# Maven Roasters Data Analysis Project

## Project Overview
This project delivers insights from an exploratory data analysis (EDA) performed on the transactional data of Maven Roasters, a coffee shop chain with three locations across New York City. The analysis evaluates sales performance, customer behavior, and product performance across the stores. The dataset includes transactional details such as dates, times, products, store locations, quantities sold, and unit prices.

---

## Check the results of the analysis in the Executive Summary [Link to the file](.Executive Summary - EDA Coffee Shop Sales.pdf)

---

## Objectives
The project aims to achieve the following:

1. **Dataset Understanding**: Examine the structure, features, and completeness of the dataset.
2. **Data Quality Checks**: Address issues like missing data, outliers, and formatting inconsistencies.
3. **Descriptive Analysis**: Summarize key performance indicators (KPIs) such as revenue, sales volume, and store performance.
4. **Visualization**: Utilize visual tools to effectively communicate trends and patterns.
5. **Identify Relationships**: Analyze correlations and patterns in customer purchases to guide business decisions.
6. **Advanced Data Analysis**: Apply advanced techniques for predictive analysis.
7. **Recommendations**: Provide actionable suggestions based on analytical insights.

---

## Motivation
The analysis was driven by Maven Roasters' need to gain deeper insights into their sales performance and customer behavior across their three store locations. Maven Roasters seeks to:

- Identify high-performing products.
- Optimize inventory management.
- Enhance customer experiences.
- Boost revenue and improve operational efficiency.

---

## Challenges Addressed
This analysis addresses key challenges and answers critical business questions:

1. **Product Performance**  
   - Which products are driving sales?
   - How do these products perform across different store locations?

2. **Customer Purchase Patterns**  
   - Are there trends based on time, day, or product category that can inform marketing or operational decisions?

3. **Store Performance**  
   - How do the three store locations compare in terms of revenue, sales volume, and customer traffic?

4. **Business Strategy**  
   - What actionable insights can be derived to improve sales and enhance the customer experience?

---
## Methodology

### Data Collection
The dataset was collected at the store level, capturing details of all transactions made at Maven Roasters' three locations. This data reflects customer purchases, including the transaction date, time, product details, and quantities sold, offering a comprehensive view of in-store activity.

### Data Preprocessing

- **Null Values and Duplicates:** The dataset was thoroughly examined for null values and duplicate records. No null values or duplicates were found, ensuring 100% data availability for analysis.
  
- **Data Type Adjustments:** Data types for certain features were updated for consistency and accuracy. For instance, categorical features such as "transaction_date" and "product_category" were converted to the appropriate formats.

### Feature Engineering

- **Date-Based Features:** 
  - **Day of the Month:** A numerical variable representing days (e.g., 1, 2, 3...).
  - **Day of the Week:** A categorical variable representing days (e.g., Monday, Tuesday, etc.).
  - **Month:** Extracted month information from the transaction date.

- **Time-Based Features:** 
  - **Hour of the Day:** Extracted from the transaction time to analyze sales patterns throughout the day.

### Transaction Value
A new feature, **Transaction Value**, was created by multiplying "transaction_qty" and "unit_price" to calculate the sales amount or revenue generated by each transaction.

---

## Analysis and Tools

The following tools and libraries were used to conduct the analysis:

- **Python:** The core programming language for data manipulation and analysis.
- **Pandas:** Used for data wrangling and manipulation.
- **NumPy:** Utilized for numerical operations.
- **Matplotlib (Pyplot) and Seaborn (sns):** Employed for creating visualizations.
- **Plotly:** Used for developing interactive charts and visual dashboards.

---

## Key Questions Addressed

- What are the top-performing products and stores?
- Are there any noticeable sales trends based on time of day or day of the week?
- How do different product categories contribute to total revenue?
- Are there correlations between product types and store locations?
- What actionable recommendations can enhance business performance?

---

## Insights and Business Implications

The analysis offers key insights that can guide strategic decision-making for Maven Roasters. Detailed results are available in the Executive Summary.

---

## Limitations and Future Work

### Limitations
- The dataset lacks customer demographics, cost details, and inventory data, limiting the scope for insights into customer segmentation and broader business operations.

### Future Work
- **Customer Analysis:** Future analyses could explore Customer Lifetime Value (CLV) and develop loyalty programs to enhance retention.
- **Dataset Expansion:** Including data on online orders and delivery sales would enable a more comprehensive view of overall performance and customer behavior.

---

## Acknowledgments

- Special thanks to the Maven Analytics team for providing the transactional data.

---
