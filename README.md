# AdventureWorks Sales Performance & Customer Insights | Power BI

## Table of Contents
## Table of Contents  
- [📌 Background & Overview](#background--overview)  
- [📂 Dataset Description & Data Structure](#dataset-description--data-structure)  
- [🧠 Design Thinking Process](#design-thinking-process)  
- [📊 Key Insights & Visualizations](#key-insights--visualizations)  
- [🔎 Final Conclusion & Recommendations](#final-conclusion--recommendations)

## 📌 Background & Overview
### 🎯 Objective:
This Power BI dashboard project analyzes sales, customer, and product data from the AdventureWorks dataset to generate actionable insights that support strategic decisions in revenue growth, customer retention, and operational efficiency.

### 📖 What is this project about?
The goal is to conduct a comprehensive analysis of AdventureWorks' sales performance from 2011 to 2014. This includes understanding product profitability, customer behavior, regional performance, churn rate trends, and return analysis.

### 👤 Who is this project for?
✔️ Sales leaders seeking a clear picture of revenue trends and profit drivers
✔️ Marketing and product teams interested in category-level performance and customer segmentation
✔️ Business strategists aiming to optimize retention and reduce return rates

### ❓Business Questions:
✔️ What are the top-performing products and regions in terms of revenue and profit?
✔️ Which customer segments generate the most value?
✔️ What factors drive customer churn and product returns?
✔️ Where are there untapped market opportunities?

## 📊 Key Insights & Visualizations  

### I. Sales Overview  

- **Total Revenue:** $12.64M  
- **Total Orders:** 25,035  
- **Total Units Sold:** 178,000  
- **Profit Margin:** 12%  
- **YoY Sales Growth:** +52%

📌 **Insights:**  
- Revenue and profit steadily increased from 2011 to 2014.  
- Sales spikes occurred mid-2012 and mid-2014, suggesting effective seasonal promotions.  
- **Top revenue markets:** US, EU, APAC  
- **Emerging opportunities:** LATAM and Africa  
- **Shipping Mode:** Standard Class dominated with over $7.6M in revenue and $0.9M profit.

---

### II. Product & Profitability Analysis  

📌 **Key Findings:**  
1. **Top Categories**  
   - 🖥️ Technology led both revenue and profit with margins ranging from 17–24%.  
   - 🪑 Furniture and Office Supplies showed stable but lower margins (8–14%).

2. **Sub-Category Performance**  
   - 📈 Top: Phones, Copiers (high revenue, 13–17% margins)  
   - 📉 Bottom: Labels, Fasteners, Envelopes (low or negative contribution)

3. **Top Products**  
   - Canon imageCLASS 2200 and Cisco Smart Phone each generated >$17K in profit.  
   - Suggest increased inventory and targeted promotions.

4. **Shipping Mode**  
   - Standard Class preferred; First Class and Same Day less popular but could serve niche segments.

---

### III. Customer Analysis  

📌 **Key Findings:**  
1. **Customer Volume & Revenue**  
   - Steady monthly growth. Peak months: November, December, September 2014.

2. **Churn Rate Analysis**  
   - Highest churn: August (24.1%), October (16.5%), January (16%).  
   - Lowest churn: February, April, May (0%), possibly due to better engagement or data issues.

3. **Segmentation**  
   - Consumer segment contributed ~51.5% (~$6.5M).  
   - Corporate: 30.25%, Home Office: 18.27%

4. **Customer Types by Region**  
   - Central, South, and North regions had >700 returning customers.  
   - New customer growth was slower—indicating strong retention, low acquisition.

5. **Customer Lifetime Value (CLV)**  
   - Highest: APAC, EU, US (avg. CLV > $9K)  
   - Lowest: Africa, Canada (avg. CLV < $2K)

---

### IV. Return Analysis  

📌 **Key Findings:**  
1. **Return Rate by Region**  
   - Highest: APAC (35.8%), LATAM (30.5%), EMEA (30.4%)  
   - Lowest: Canada (0%), Africa (21.4%)

2. **Monthly Return Trends**  
   - Peaks in February, October, and December—aligning with seasonal sales surges.

3. **Returns by Segment & Category**  
   - Technology had the highest return rate (~33%)  
   - Corporate segment returned more Office Supplies  
   - Consumers returned more Furniture and Tech

4. **Sub-Category Return Rates**  
   - Highest: Chairs (32.3%), Phones (32.2%), Binders (26.9%)  
   - Binders and Storage had the highest total returns by volume.

5. **Top 10 Returned Products**  
   - Smead File Folders, Rogers File Cabinet, Ibico Index Tabs, Rogers Lock File were the most returned.

---

## 🔎 Final Conclusion & Recommendations  

| Strategy                      | Insight                                                                 | Recommendation                                                                 |
|------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| 🚀 Market Expansion           | Canada and Africa have low sales but minimal competition                | Launch localized campaigns, leverage referrals, and target engagement          |
| 🧠 Product Optimization       | Phones and Copiers drive margin; Labels and Fasteners underperform      | Scale high performers, repackage or remove low-profit SKUs                    |
| 👥 Retention Strategy         | August and October show high churn spikes                               | Add churn monitoring and post-promo engagement campaigns                        |
| 🛒 Customer Acquisition       | Slow growth in new customers across regions                              | Build stronger onboarding and tailored first-purchase incentives              |
| ⚙️ Shipping Efficiency        | Standard Class dominates; others underused                              | Keep Standard Class default; offer upgrades to high CLV users                 |
| 🔄 Return Management          | High return rates in APAC, LATAM, EMEA                                  | Improve product info, packaging, AR demos, and localized quality control       |

---

## Sales Dashboard

**1.Sales Overview**
![png](https://github.com/caseytientruong/PowerBI-Adventure-Works-Analytics/blob/main/Overview.png)


**2. Product & Profitability**
![png](https://github.com/caseytientruong/PowerBI-Adventure-Works-Analytics/blob/main/Product.png)


**3. Customer Analysis**
![png](https://github.com/caseytientruong/PowerBI-Adventure-Works-Analytics/blob/main/Customer.png)


**4. Return & Shipping**
![png](https://github.com/caseytientruong/PowerBI-Adventure-Works-Analytics/blob/main/Return.png)

