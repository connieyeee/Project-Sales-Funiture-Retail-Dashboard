# Project-Sales-Funiture-Retail-Dashboard
The data, content, and final delivery I shared on GitHub utilize mock-up data due to confidentiality.The main goal of this project is to demonstrate my expertise in data analysis, modeling, and problem-solving.

## Table of Contents

1. [Introduction](#introduction)
2. [Specifications](#specifications)
3. [Dataset](#dataset)
4. [Results](#results)
    - [Proof of Concept Dashboard Design](#proof-of-concept-dashboard-design)
    - [Technical Challenges - Highlights](#technical-challenges-highlights)
    - [Business Insights - Recommendations](#business-insights-recommendations)
5. [Lessons Learned](#lesson-learned)

---

## 1. Introduction <a name="introduction"></a>
The primary objective of this dashboard is to rigorously model, measure, analyze, and continually monitor the sales performance within the furniture department store. By harnessing the insights extracted from the accessible Orders, People, and Returns datasets, the dashboard facilitates a comprehensive understanding of sales and orders. Through the implementation of predefined dimensions and key performance indicators, it generates three distinctive analyses: sales summary, product detail, and customer detail. These analyses are thoughtfully designed to address the specific information requirements of diverse stakeholders, empowering them with actionable insights to drive data-informed decisions and optimize the furniture department store's performance.

## 2. Specifications <a name="specifications"></a>
The analysis encompasses crucial measures, including cost of goods sold, year-over-year sales growth by order date, sales amount discounted, consumer sales, amount returned, rolling 4-month sales by order date, last data model refresh, and total sales by both month ordered and month shipped.

The dashboard is structured into three pages: Sales Summary, Product Detail, and Customer Detail.

1. **Sales Summary Page**: Catering to the executive team, this page offers a comprehensive high-level overview of year-over-year sales and gross margin performance trends compared to the previous year. It segments data by product category, customer segment, time period, and region, while showcasing key performance indicators such as sales amount, gross margin, and cost.

2. **Product Detail Page**: Tailored to assist the sales and marketing teams, this page provides in-depth insights into individual product performance. It enables the refinement of operational strategies and facilitates the delivery of targeted marketing campaigns.

3. **Customer Detail Page**: Designed for the CRM and marketing campaign department, this page offers valuable insights into customer behaviors. Utilizing top N analysis, it identifies the most valuable customers and evaluates the contribution of each customer segment to the total sales amount.

## 3. Dataset <a name="dataset"></a>

The dataset consists of a total of 9 tables, comprising 3 source data tables and 6 data mart tables.

1. **Orders**: This fact table contains essential information such as customer code, order code, order date, postal code, last product update, and product code.

2. **People**: Provides detailed information about individuals (customer names) and regions.

3. **Returns**: Contains data on order codes and indicates whether a product has been returned.

4. **Calendar**: Includes a single record for each date used in the analysis.

5. **Customer**: Derived from the order table, it includes customer details such as customer code, customer name, and segment.

6. **Date Type**: Specifies the type of date, either order date or ship date.

7. **Last Refresh**: This table updates and returns the latest refresh time each time the dashboard is refreshed.

8. **Product**: Derived from the order table with a predefined filter, it includes product details such as product code, category, sub-category, product name, and last product update.

9. **Region**: Derived from the order table, this table contains comprehensive information about postal code, country, state, city, and region.

