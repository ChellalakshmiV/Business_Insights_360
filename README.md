# Business Insights 360

### Project Overview:

AtliQ Hardware is a hardware company supplying products like PCs, mice, and printers to various retailers such as BestBuy, Chroma, Staples, and online platforms like Amazon and Flipkart. These retailers then sell the hardware to end consumers through brick-and-mortar stores or e-commerce platforms and operates through three channels: retailer, direct, and distributor, catering to both physical and online sales channels. The company is growing rapidly and has decided to start using Power BI for data analytics. This decision is aimed at staying ahead of competitors and making decisions based on data. The project will focus on answering questions from stakeholders in finance, sales, marketing, and supply chain departments.

### Live Dashboard:

Explore the live dashboard: 
[Project Link](https://app.powerbi.com/view?r=eyJrIjoiMjgxZGU0NDctNGViZC00NDU1LWIzMTgtY2ZiM2Y2ZmY4MmQwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

### Data Sources:

The dashboard seamlessly collects and utilizes data from two primary sources:
- **Excel/CSV Files** - Targets, Market Share data, and related information
-	**MySQL Database** - Dimensions and Fact data over million of rows of data

### Project Toolset Overview:

-	Power BI Desktop
-	MySQL
-	Microsoft Excel
-	DAX language
-	DAX studio (for optimizing the report)
-	Project Charter file

### AtliQ Hardware's Data-Driven Evolution:

AtliQ Hardware, a leading hardware company that produces a range of products such as PCs, mice, printers, and more. The company has seen substantial growth in electronics goods but faced experienced setbacks in the American market due to inadequate decision-making based on surveys and intuition. To rectify this, they swiftly transitioned to data-driven strategies. Recognizing the urgency spurred by competitor actions, they promptly hired a dedicated data analytics team. This shift underscores AtliQ's commitment to leveraging data for strategic decision-making and risk mitigation. By embracing data analytics, AtliQ aims to enhance market presence and sustain growth momentum.

### Project Kick-Off Meeting - Creation of Project-Charter:
Before diving into the dashboard development, it's important to address some questions:

1. **Project Objectives:** What is the primary purpose of this project and specific objectives are we aiming to achieve?
2. **Required Resources:** What data and resources are needed to build this dashboard?
3. **Success Measures:** What metrics will we use to gauge the project's success?
4. **Project Timeline:** What is the proposed timeline for completing the project?
5. **Preview Expectations:** Are there any expectations for providing a preview or demo version of the project before its official completion?
6. **Stakeholder Expectations:** What are the stakeholders' hopes and fears regarding this project? Are there specific benchmark numbers or standards that stakeholders expect us to use for validating and cross-checking data accuracy?
7. **Dashboard Users:** Who are the intended users of the dashboard, and what do they aim to accomplish by using it?
8. **Defining success:** How do you envision encapsulating success in a headline? Which precise metrics or benchmarks will guide our evaluation of success?
9. **Risk:** What are the potential risks and uncertainties associated with this project?
10. **Stakeholder mock-up preference:** Can you share any mock-up dashboard of each page view?
    
### Main Features:

- **Home view:** Presented all available views from the report, allowing users to toggle between each one.
- **Finance View:** Delved into detailed financial metrics, encompassing revenue, expenses, and profit margins. Evaluated key performance indicators such as Net Sales, Gross Margin %, and Net Profit %. Developed a comprehensive Profit and Loss Statement showcasing year-over-year growth.
- **Sales View:** Provided a deeper understanding of product and customer performance. Explored Customer Performance metrics based on Net Sales and Gross Margin.
- **Marketing View:** Augmented marketing strategies with segmented performance insights and Net Profit metrics.
- **Supply Chain View:** Identified optimization opportunities for efficient supply chain management. Analysed variances between Actual Sales and Forecast accuracy.
- **Executive View:** Presented critical metrics tailored for top-level decision-makers. Examined yearly trends in revenue, Gross Margin %, Net Profit %, and Market Share %. Highlighted the top 5 Customers & Products contributing to revenue.
- **Sales Trend (Tooltip)**

### Insights:
### Analysis of Business Performance: Understanding the Dynamics Behind Revenue Growth and Profit Decline

**Financial Highlights:**
- In 2020, the company experienced a substantial increase in net sales, reaching ₹267.98 million, marking a remarkable 140.61% surge compared to 2019. While this growth in net sales is commendable, a deeper analysis reveals a concerning trend.
- Despite a significant 116.66% increase in gross margin compared to the previous year, there was a notable decline in net profit, plummeting by ₹4.75 million, representing a staggering 193% decrease from 2019.

**Profitability Challenges:**
- Upon closer examination, it becomes evident that this decline in net profit can be attributed to a considerable rise in operational expenses, amounting to over ₹58 million more than the expenses incurred in the preceding year.
- This underscores the need for strategic management of expenses to maintain profitability.

**Profit Decline Concern:** 
- In 2021, while both net sales and gross margin experienced impressive growth, exceeding 200%, there was a significant concern regarding net profit.
- It dropped to ₹54 million, marking a drastic 2286% decrease compared to the previous year.
- This sharp decline underscores the critical importance of monitoring and addressing net profit, a pivotal metric for assessing the company's growth trajectory.

**Regional Profit Analysis:**
- In 2021, the company experienced notable challenges in net profit, particularly in the APAC and NA regions. Within the APAC region, India saw a significant decline, possibly due to excessive spending on advertisements and operational expenses, which surpassed ₹119 million.
- Similarly, in the NA region, there was a decline in net profit, with a difference of ₹23 million compared to the previous year. Further analysis suggests a need to examine sales and expenses related to the notebook segment in the USA region.

**Customer Preference:**
- Across all years, Amazon, AtliQ Exclusive, and AtliQ eStore consistently alternate as the top customers, securing the top positions in the list due to their significant contribution to gross margin.

**Product Preference:**
- The notebook segment stands out as the leading product category, generating the highest gross margin for the company.

### Recommendations:

Based on the following analysis, the recommended actions are,

1. **Cost Management:** Implement measures to control expenses, particularly in regions where significant overspending is observed, to improve overall profitability.
2. **Product Strategy:** Capitalize on the popularity of the notebook segment by investing in product innovation, marketing, and distribution channels to maximize gross margin and overall revenue.to address the decline in net profit observed in the NA region.
3. **Operational Efficiency Strategy:** Continuously monitor and adjust advertising and operational expenses in regions like APAC to ensure efficient utilization of resources and maximize profitability.
4. **Customer Focus:** Further analyze the customer preferences and tailor marketing strategies to capitalize on top-performing customer segments like Amazon, AtliQ Exclusive, and AtliQ eStore for maintaining the consistency in gross margin performance.

Below are the  data model and all other views of my dashboard report.

### Data model:

![Data model](https://github.com/ChellalakshmiV/Business_Insights_360/assets/162456368/8fc413df-54cc-4cad-b9af-fbaa935941ea)

**Home view:**

![Home view](https://github.com/ChellalakshmiV/Business_Insights_360/assets/162456368/f2363fd5-723c-43f7-9875-f3c22ce6edef)

**Finance View:**

![Finance view](https://github.com/ChellalakshmiV/Business_Insights_360/assets/162456368/d71a69c2-e4da-43f6-a413-933d7fc5015d)

**Sales View:**
![Sales view](https://github.com/ChellalakshmiV/Business_Insights_360/assets/162456368/92dfd27d-c18b-4436-bf92-4427aff42617)

**Marketing View:** 

![Marketing view](https://github.com/ChellalakshmiV/Business_Insights_360/assets/162456368/913fb09b-0a76-4aab-a82d-4b81894c7d4e)

 **Supply Chain View:** 

 ![Supply chain view](https://github.com/ChellalakshmiV/Business_Insights_360/assets/162456368/c227db2b-540f-44ca-8363-7e7076f4bb50)

 **Executive View:**

 ![Executive view](https://github.com/ChellalakshmiV/Business_Insights_360/assets/162456368/326c57eb-6db8-410a-9ec8-bc6a400a1f42)

**Sales Trend (Tooltip):**

![Sales Trend Tooltip](https://github.com/ChellalakshmiV/Business_Insights_360/assets/162456368/405e2ff5-4399-47f5-ae3d-8bf706a8f694)


