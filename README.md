# Unveiling Trends: A Comprehensive Four-Year Sales Data Analysis
---
## Project Overview
The primary objective of this project is to conduct an in-depth analysis of four years' worth of sales data from 2014 to 2017 to uncover key trends, patterns, and insights that will inform strategic decision-making for the organization. By dissecting the data, the project aims to provide actionable recommendations to enhance sales performance, optimize resource allocation, and identify areas for growth.

The project covers a comprehensive exploration of sales data spanning four years, examining various dimensions such as product categories, customer segments and geographical regions. The scope encompasses both macro and micro perspectives, delving into overarching trends while zooming in on specific products, segments, and their interactions.

![](Dataset)
![Screenshot 2024-01-09 003939](https://github.com/ziraefrimpong1/Superstore-Data-Analysis/assets/154938134/ee5d5470-b949-4042-be0e-ddea61247b96)

We will resolve this case following this methodology:

`ASK, PREPARE, PROCESS, ANALYSE, SHARE AND ACT`

---

## **ASK**
This phase involves defining the issue to be solved, identifying stakeholders and what their expectations from the project are.

Four questions will guide the future marketing program:

1. What are the key drivers of sales performance?
   
    - Which products or categories contribute the most to revenue?
  
    - Are the specific time periods or seasons with higher sales?
  
2. How can customer segmentation be leveraged to enhanve the overall shoppping experience and increase customer loyalty?

   - Can distinct customer segments be identified based on purchasing behavior?
     
   - What are the preferences and buying patterns of different customer segments.

3. How can we optimize our shipping strategy to align with customer preferences and enhance overall satisfaction?

   - What ship mode is most prefered by customers, and how does it align with their expectations?
  
   - Are there opportunities to tailor shipping options based on customer preferences to enhance overall satisfaction?
  
4. How can can discount levels be optimized to maximize overall sales volume?

   - How do different discount levels influence overall sales volume?
  
   - Can you identify specific products or categories where discounts have a more significant impact on sales?


### Business Task
Analyze and leverage key drivers of sales performance, including product contribution to sales, seasonal sales patterns, and customer segmentation.

### Key Stakeholders
- **Marketting Analytics Team**: A team of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy.
  
- **Executive Team**: The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.
---

## PREPARE
Involves collecting data and information and ensuring it satisfies necessary parameters.

### Data Location
The dataset was obtained from Kaggle. Click [here](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls)
to download it.

### Data Organization
The dataset contains 9999 rows and 21 columns.

#### `Features:`

**Row ID** => Unique ID for each row.

**Order ID** => Unique Order ID for each Customer.

**Order Date** => Order Date of the product.

**Ship Date** => Shipping Date of the Product.

**Ship Mode** => Shipping Mode specified by the Customer.

**Customer ID** => Unique ID to identify each Customer.

**Customer Name** => Name of the Customer.

**Segment** => The segment where the Customer belongs.

**Country** => Country of residence of the Customer.

**City** => City of residence of of the Customer.

**State** => State of residence of the Customer.

**Postal Code** => Postal Code of every Customer.

**Region** => Region where the Customer belong.

**Product ID** => Unique ID of the Product.

**Category** => Category of the product ordered.

**Sub-Category** => Sub-Category of the product ordered.

**Product Name** => Name of the Product

**Sales** => Sales of the Product.

**Quantity** => Quantity of the Product.

**Discount** => Discount provided.

**Profit** => Profit/Loss incurred.

---
### Tool
The tool used for this project is Microsoft Excel 2016.

---

## PROCESS
This phase of the analysis process includes cleaning the data and making sure it is fit for purpose. As well as making any modifications necessary.

A summary of the cleaning and manipulation done to the data is presented below:

1.	Removed 5 duplicate values which reduced the number of rows from 9999 to 9994.
2.	No blank row found in dataset.
3.	Checked for consistency of ship_date and order_date (Nested the IF() and OR() functions to ensure ship_date is greater than or equal to order_date).
4.	Changed sales and profit columns General datatype to currency datatype.

---


## **ANALYZE**

In this phase we analyze the data using statistical methods to find patterns, relationships, and trends.


**Outlined below are the key takeaways derived from the analysis of the data:**
1. The company's total sales have been consistently increasing over the years, indicating a positive growth trend shown by the chart below.
This insight suggests that the company's sales efforts and strategies have been effective in driving revenue and capturing market share. It showcases the company's ability to generate increasing sales figures over time, which is a positive indication of its performance and market competitiveness.

   ![](Overall_Sales_Trend)
   ![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/60fbe522-1d02-4188-94ef-74ff74c231b5)
---

2. A compelling insight emerges from the data, revealing that New York City stands out significantly with the highest total sales volume of $256K, indicating unique factors contributing to its robust sales performance. Moreover, the Canon imageCLASS 2200 Advanced Copier demonstrates exceptional resonance with customers, generating over 2x more sales revenue than the next highest-selling product and constituting 25% of total sales among the top 10 products, showcasing distinctive qualities that captivate consumers.
  
   On the other end, the Eureka Disposable Bags for Sanitaire Vibra Groomer Upright Vac, with a sale of $2.00, represents the least sold product, providing a point of interest for further analysis and potential optimization.
   
   ![](Top_10_Products_and_Cities)

   ![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/83bb297a-d956-43d1-a254-5f0a2ea9d17f)

---

3. A significant insight derived from the data is that the Technology category contributes 37% to total sales revenue, surpassing both Furniture and Office Supplies, which account for 32% and 31% each respectively. Additionally, despite the Corporate and Home Office segments contributing 31% and 19% to total sales revenue respectively, the Consumer Segment stands out, accounting for 50%.

   This highlights the substantial influence of the Consumer Segment in driving a disproportionate share of the overall business, suggesting potential areas for targeted strategies and further exploration to capitalize on the strength of the Consumer Segment."

    ![](Sales_Contribution_by_Category_and_Segment)
   ![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/6fccdfc9-4cfe-473e-bca6-e48ec3223b13)

---

4. The Phones Sub-Category significantly outperforms all other Categories in total sales volume with the maximum sales of $330K. 

   A pivotal insight emerges from the data, indicating that while the Phones sub-category leads in overall sales, the Chairs sub-category demonstrates superior performance within specific segments. Notably, in the Consumer segment, Chairs lead with $173K compared to Phones' $170K, and in the Corporate segment, Chairs lead with $99K compared to Phones' $91K. This nuanced view underscores the importance of segment-specific strategies, revealing opportunities for targeted efforts to further enhance the success of the Chairs sub-category within distinct market segments.
    
   ![](Preference_from_Top5_Sub-Category)
![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/7cae844d-85d6-4bf3-82b4-2bae04c03b90)

---

5. A significant insight from the data indicates a positive correlation between sales and quarters, revealing an increase in sales with each subsequent quarter. Notably, Q4 emerges as the top-performing quarter, leading with a maximum sale of $100K. 
This indicates Q4 has unique drivers of sales volume, most likely holiday shopping and end-of-year budget spending.

   ![](Sales_Performance_by_Quarter)
   ![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/71154a8e-e3df-4e66-ab82-e9c21a9d9cd7)

---

6. A pivotal insight from the chart highlights fluctuations in sales throughout the months. The chart reveals a substantial peak in sales on September, December and November, with November reaching the highest recorded sales revenue of $252K. Conversely, the month of February records the least sales of $60K.

   ![](Sales_Trend_by_Month)
   ![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/346c8342-063d-48cd-89aa-44c6f15abafe)

---


7. The Phones and Chairs categories both see their peak sales at a 20% discount, outpacing other discount levels and Sub-Categories. This suggests Phones and Chairs have the most price- sensitive customer base.

   ![](Impact_of_Discount_on_Specific_Products)
   ![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/20a627ea-271e-4aed-9a13-f77eeecf8423)

---

### **Dashboard 1**

![](Dashboard_1)
![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/fa3ce17e-cfdb-4ec8-8d62-cd0867031784)

---

### **Dashboard 2**

![](Dashboard_2)
![image](https://github.com/ziraefrimpong1/Excel-Project-2/assets/154938134/90ebae28-38c7-4f07-ba12-052a22c13dec)

---

## ACT
Upon completion of data processing, analysis, and insight dissemination, the conclusive phase involves formulating a well-aligned course of action for the Superstore enterprise, congruent with its business goals and mission. My recommendations are as follows:

1. **Continued Investment in Successful Sales Strategies**

   Leverage the strong sales growth by continuing effective sales strategies and efforts. Continue investing in and evolving these strategies to maintain positive momentum and drive       sustained revenue growth.

3. **New York City-Specific Marketing Initiatives**

   Prioritize New York City for tailored strategies to maintain robust sales. Further research will be required to identify unique drivers of performance such as understanding local preferences and consumer behaviours to optimize sales performance in this key market.
   
4. **Optimization of Product Portfolio**

   Given the exceptional performance of the Canon imageCLASS 2200 Advanced Copier, consider optimizing the product portfolio to emphasize or expand similar high-performing products. This includes potential enhancements or marketing strategies to further capitalize on consumer preferences

   Investigate the Eureka Disposable Bags for Sanitaire Vibra Groomer Upright Vac, which represents the least sold product. Further research will be required to understand the reasons behind its underperformance and explore potential optimization strategies or product adjustments.

5. **Strategic Focus on Consumer Segment**

   Acknowledge the disproportionate influence of the Consumer Segment, constituting 50% of total sales revenue. Develop targeted marketing campaigns and engagement strategies to further tap into the strength of the Consumer Segment.

6. **Segment-Specific Strategies for Phones and Chairs**

   Prioritize Phones for driving overall sales volume. However, develop segment-specific strategies to boost Chairs in Consumer and Corporate segments.

7. **Strategic Planning for Peak Quarters and Months**

   Leverage insights from the positive correlation between sales and quarters with a focus on the unique drivers of sales volume in Q4. Further research will be required to identify the unique drivers of sales volume in Q4. Additionally, strategically plan for peak months, particularly September, December, and November, to maximize sales during these periods of heightened consumer activity.

8. **Pricing Strategies for Phones and Chairs**

   Offer strategic discounts on Phones and Chairs in September, November, and December to align with peak sales months. Avoid discounts in slower months like February.

 ---
 
## CONCLUSION
Throughout the duration of this project, I have effectively utilized Excel to carry out tasks such as data cleansing, processing, analysis, and data visualization. These efforts have enabled me to extract valuable insights from the data in alignment with the principles of the Google Data Analytics Certification program.

---

## REFERENCES

**Emmanuel Anene**: Data Analytics Project: Sales Analysis Report [LINK](https://emmanuelanenee.medium.com/data-analytics-project-sales-analysis-report-7a718049fecc)

**Google Data Analytics Professional Certificate**.
