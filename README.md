# 📊 Vertex Nexus Sales EDA Project

🔗 [Open the Exploratory Analysis Notebook](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/Vertex_Nexus_EDA.ipynb)

Exploratory Data Analysis (EDA) on sales data from **Vertex Nexus**, aimed at uncovering key trends Customer-wise, State-wise and Product-wise. This project demonstrates my Python data analysis workflow—from data cleaning to Analysis.

## 🧠 Overview

This project explores sales patterns to answer questions like:
- How do sales vary across different Customer Category?
- Which regions generate the most revenue?
- What product categories are driving growth?
- Which aspects should the company focus on to drive growth and improve sales?

## 🛠️ Tools & Technologies

- **Python** 🐍  
  - pandas for data manipulation  
  - matplotlib, seaborn for visualizations  
  - plotly for interactive charts  
- **Google Colab** for iterative analysis  
- **GitHub** for Project Presentation   


## About Business

Vertex Nexus Pvt Ltd  is a dynamic, multi-sector enterprise based in India. It operates across several high-impact industries and deals in multiple products.

## Objective

The Vertex Nexus sales team has observed several pressing issues impacting overall business growth:
- Stagnant Sales for Specific Products: Certain products have not shown consistent growth, prompting concerns about market relevance, pricing, or promotional strategy.
- Underperforming Geographic Areas: Specific regions are contributing below-average revenue, indicating potential issues in market penetration, channel effectiveness, or local demand.
- Limited Customer Segmentation Insight: The company seeks to better understand its customer base—particularly identifying high-value customers and behavioral patterns—to unlock new sales opportunities and refine targeting strategies
As a data analyst, my goal is to perform Exploratory Data Analysis (EDA) on the Vertex Nexus sales dataset to uncover insights and provide solutions.

## 🧹 Data Cleaning & Transformation

- Removed the Status and unnamed1 column from the data as they were empty
- Removed Null Values from Amount Column
- Changed The Amount Column data type as integer

## 📈 Key Insights

### Explored Data on the basis of customers

Calculated Gender-wise Revenue and Count of Customers Chart

![Gender-wise Count](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/59a7ab5ba1ef73e73f40e5a6f112d904df9e7f2a/outputs/visuals/gender-wise%20count.png)
![Gender-wise Revenue](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/5066cefd97e0cac4906c6a30fbbc6a3fd0ab7a74/outputs/visuals/gender-wise%20revenue.png)

**Females account for more than 50% of the total customers and spent more than 70 million whereas Males spent only around 30 million**

Calculated Age-wise Revenue and Count of orders chart

![Age-wise Count](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/age-wise%20count.png)
![Age-wise Revenue](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/age-wise%20revenue.png)

**26-35 age group is the top spender with females spending the most whereas 0-17 age group spent the least amount.**

Calculated Marital Status-wise Count of Orders and Revenue Chart

![marital_status-wise Count](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/marital%20status%20count.png)
![marital_status-wise Revenue](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/marital%20status%20revenue.png)

**Unmarried Females Generated maximum amount of revenue, a potential target customer**

Calculated Occupation-wise Count and Revenue Chart

![occupation-wise Count](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/occupation-wise%20count.png)
![occupation-wise Revenue](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/occupation-wise%20revenue.png)

**IT and Healthcare sector customers generated most amount of Revenue, can give offers and discounts to the underperforming sectors to raise their levels.**

### Explored data on the basis of States

Calculated state-wise Revenue and Count of orders Chart for Top 10 states

![State-wise Count](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/top%2010%20states.png)
![state-wise Revenue](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/states%20revenue.png)

***Uttar Pradesh is giving max number of orders and generating max revenue.**
**Analysed although Kerala is bringing more number of orders than Haryana and Gujarat but the Revenue generated by both states is more than Kerala meaning average order amount is less in Kerala.**

### Explored Data on basis of Product Category

Calculated Product Category-wise Revenue and Count of orders and Top 10 Products Chart

![product-wise Count](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/product_category-wise%20count.png)
![product-wise Revenue](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/product_category-wise%20revenue.png)
![Top 10 products](https://github.com/Deepanshu985/Vertex_Nexus_Sales_EDA/blob/e8e2d90d3c68c102394258e20aae75178e73e286/outputs/visuals/top%2010%20products.png)

**Both Food and Clothing are bringing max number of orders and generating max revenue.
Identified Products which are not performing well - they should be analysed further to find problems and decide if the company should keep them or put their resources on categories with higher benefit.**

### Conclusion

**Unmarried woman in age group 26-35 years old from UP, Maharashtra and Karnataka working in IT, Healthcare and Aviation are more likely to buy products from Food, Clothing and Electronics Category.**

### Recommendations

1. More offers should be given to Unmarried women to boost sales and revenue as they are high ordering customers.
2. States where sales are lacking should be analysed further and targeted marketing campaigns should be done.
3. Products with higher sales should be kept in stock and their inventory levels should be in checks.
4. Products with minimal sales should be analysed if it is profitable for company to keep them or close them and these resources can be used to create products for different occupation-wise     customers to increase their engagement and trying to target different customer segments.

#### Thank you for exploring this analysis!  ####

