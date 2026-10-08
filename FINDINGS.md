# Northwind Global Sales & Operations — Key Findings

## Overview

This document summarizes the main business insights identified from the Northwind Traders sales and operations data.

The analysis was carried out in Power BI after cleaning, transforming, modelling and validating the underlying transactional data.

The goal was not only to visualize the numbers, but to understand what they suggest about sales performance, products, markets, logistics and salesforce productivity.

---

## 1. Overall Sales Performance

Northwind recorded approximately **$1.27 million in revenue** across **830 orders**, with **51,317 units sold**.

The average order value was approximately **$1,525**, while total freight costs were approximately **$64.9K**.

Revenue increased significantly across the available years:

- 2013: approximately **$208.1K**
- 2014: approximately **$617.1K**
- 2015: approximately **$440.6K annualized run-rate** based on the available data through early May

The monthly trend also showed recurring increases in order activity toward the final quarter of the year.

April 2015 recorded one of the strongest monthly revenue performances in the available dataset, at approximately **$123.8K**.

### Interpretation

The business experienced strong growth between 2013 and 2014. The recurring Q4 increase in activity also suggests a seasonal component to demand.

However, the 2015 figure should be interpreted carefully because the available data only extends into early May.

---

## 2. Product and Category Performance

The analysis showed that **Beverages** and **Dairy Products** were the strongest revenue-generating categories.

Together, they contributed approximately **39.7% of total revenue**.

Beverages generated approximately **$267.9K**, while Dairy Products generated approximately **$234.5K**.

At the product level, **Côte de Blaye** was the strongest revenue-generating product, contributing approximately **$141.4K**, or about **11.2% of total company revenue**.

Another major contributor was **Thüringer Rostbratwurst**, with approximately **$80.4K in revenue**.

### Interpretation

Revenue is concentrated around a relatively small number of products and categories.

This means management should pay particular attention to the availability, pricing and distribution of high-performing products because disruptions in these products could have a noticeable effect on overall revenue.

---

## 3. Discontinued Products

The product portfolio contained:

- **69 active products**
- **8 discontinued products**

Discontinued products represented only approximately **10.4% of the product catalogue**, yet they generated approximately **$185K**, representing about **14.6% of historical revenue**.

Some discontinued products were still significant contributors to sales.

### Interpretation

This creates an important management question.

A product being discontinued does not necessarily mean it has little commercial value.

Products such as Thüringer Rostbratwurst and Alice Mutton demonstrate that some discontinued products continued to generate meaningful revenue.

Before completely removing such products from the portfolio, management could investigate:

- Remaining customer demand
- Profitability
- Supply constraints
- Replacement products
- Customer dependence on the product
- Historical sales trends

---

## 4. Discount Impact

Total discounts amounted to approximately **$88.7K**, representing a discount rate of approximately **6.55%** of gross sales.

The highest category-level discount rate was recorded in **Meat & Poultry**, at approximately **8.51%**.

This represented roughly **$15.2K in discounts** on approximately **$178.2K in gross sales**.

### Interpretation

Discounting appears to be an important sales lever, but the effect should be monitored carefully.

A higher discount rate may help generate volume, but without product cost data it is not possible to determine whether the additional sales actually produced higher profit.

Management should therefore monitor discount levels alongside:

- Revenue
- Units sold
- Order volume
- Product costs
- Gross margin

---

## 5. Regional Market Performance

Revenue was distributed across multiple countries and cities.

Some of the strongest cities by revenue included:

- Cunewalde — approximately **$110K**
- Graz — approximately **$105K**
- Boise — approximately **$104K**

The analysis also identified markets where freight represented a relatively high proportion of revenue.

The highest freight burdens included:

- Argentina — **7.37%**
- Sweden — **5.92%**
- Austria — **5.80%**

Overall freight represented approximately **5.13% of revenue**.

### Interpretation

High-revenue markets are not necessarily the most efficient markets operationally.

Markets such as Argentina, Sweden and Austria may require additional investigation into:

- Shipping routes
- Order sizes
- Carrier selection
- Delivery distance
- Freight pricing
- Customer location
- Order consolidation opportunities

---

## 6. Shipper Performance

The analysis showed different trade-offs between shipping speed, cost and reliability.

### Federal Shipping

- Average delivery: **7.47 days**
- On-time rate: **96.39%**
- Freight per order: approximately **$81.78**

### Speedy Express

- Average delivery: **8.57 days**
- On-time rate: **95.10%**
- Freight per order: approximately **$65.45**

### United Package

- Orders: **315**
- Revenue transported: approximately **$533.5K**
- Freight per order: approximately **$87.48**
- Average delivery: **9.23 days**
- On-time rate: **94.92%**

### Interpretation

The carriers demonstrate different operational trade-offs.

Federal Shipping recorded the strongest combination of delivery speed and on-time performance, while Speedy Express had the lowest freight cost per order among the three.

United Package handled a substantial volume of business but recorded the slowest average delivery time and the highest freight cost per order.

Management should therefore avoid evaluating carriers using cost alone.

A more complete carrier scorecard should consider:

- Freight cost
- Delivery speed
- On-time performance
- Order volume
- Revenue transported

---

## 7. Salesforce Performance

The employee analysis showed noticeable differences in revenue contribution and order volume.

The strongest revenue contributors included:

- Margaret Peacock — approximately **$232.9K**
- Janet Leverling — approximately **$202.8K**
- Nancy Davolio — approximately **$192.1K**

There were also differences in average order value.

For example:

- Anne Dodsworth handled approximately **43 orders** and generated about **$77.3K**, with an average order value of roughly **$1,798**
- Andrew Fuller handled approximately **96 orders** and generated about **$166.5K**, with an average order value of roughly **$1,735**
- Laura Callahan handled approximately **104 orders** and generated about **$126.9K**, with an average order value of roughly **$1,220**

### Interpretation

Salesforce productivity should not be evaluated only by the number of orders handled.

Revenue, order volume and average order value provide a more useful picture of individual performance.

An employee with fewer orders may still generate strong revenue because of a higher average order value.

---

## 8. Logistics Efficiency

Across the dataset:

- Average delivery time: approximately **8.49 days**
- On-time rate: approximately **95.43%**
- Total freight: approximately **$64.9K**
- Freight as a percentage of revenue: approximately **5.13%**

There were **21 orders without a shipped date**.

These orders were treated as **Not Shipped** rather than Late.

### Interpretation

The overall on-time delivery rate is strong, but the unshipped orders should be monitored separately.

Treating an order with no shipped date as late would distort the shipping performance analysis because there is no actual shipment date to compare with the required delivery date.

---

## 9. Key Business Takeaways

The analysis suggests five major areas of attention for management:

### 1. Protect high-value products

A small number of products contribute a significant portion of total revenue. Their availability and supply should be closely monitored.

### 2. Review discontinued products

Some discontinued products continue to generate meaningful revenue. Their discontinuation decisions should be reviewed against actual customer demand and profitability.

### 3. Monitor discounting

Discounts are generating sales activity, but the business needs product cost and margin information to determine whether higher discounting is creating profitable growth.

### 4. Optimize freight

Overall freight is manageable relative to revenue, but some markets and carriers have disproportionately high freight burdens.

### 5. Evaluate salesforce productivity holistically

Revenue, order volume and average order value should be considered together when evaluating employee performance.

---

## 10. Data Limitations

There are several limitations to this analysis.

### Profitability

The dataset does not contain product acquisition cost, COGS or operating costs.

Therefore, true gross profit or net profit could not be calculated.

The analysis instead focuses on revenue, gross sales, discounts and discount rates.

### Market Share

The geographic analysis represents Northwind's internal revenue distribution.

It should not be interpreted as external market share because no external market-size data was available.

### Shipping Data

There were 21 orders without a shipped date.

These were classified as Not Shipped rather than Late.

### Partial 2015 Data

The dataset only covers part of 2015, so direct annual comparison between 2015 and complete years should be treated carefully.

---

## Conclusion

This project showed how transactional sales data can be transformed into a business intelligence solution that supports decisions across sales, products, logistics and people performance.

The most important lesson from the analysis is that a dashboard should go beyond displaying numbers.

The real value comes from connecting those numbers to business questions and identifying where management may need to investigate further.
