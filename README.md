# AGRICULTURAL RESEARCH ANALYSIS 
### Table of Contents
- [Introduction](#Introduction)
- [Problem Statement](#Problem-Statement)
- [Data Collection](#Data-Collection)
- [Tool](#Tool)
- [Preprocessing](#Preprocessing)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Insights](#Insights)
- [Dashboard](#Dashboard)
- [Recommendation](#Recommendation)
  
### Introduction 
This research project aims to analyze and enhance the understanding of the unit economics within the agriculture and grocery sectors in gauteng province, South Africa. By examining the value chain for produce, the study seeks to uncover critical insights into the gross margins at various levels of the supply chain, including farmers, wholesalers, distributors or agents, and grocery retailers.

The research also focuses on the geographical distribution of agricultural activities across South Africa, identifying key provinces with significant farming activities. A particular emphasis is placed on Gauteng Province, investigating the number of operational farms and their major types of produce.

This report serves as a foundation for informed decision-making, enabling stakeholders to optimize operations, improve profitability, and foster sustainable practices in the agriculture and grocery sectors. Insights derived from this study will also contribute to developing strategies that support farmers and enhance food supply chain efficiency.

### Problem Statement
To enhance agricultural productivity and resource allocation in South Africa, there is a need to analyze the distribution and scale of farming activities across provinces and evaluate crop and animal production within Gauteng. The goal is to identify trends, disparities, and potential areas for improvement in agricultural output and sustainability, leveraging insights from farm distribution, land usage, and production metrics.
This analysis involves estimating gross margins at each stage of the value chain and identifying regional and production-specific trends. Specifically:
- Determine which provinces host the majority of farms and analyze the types of agricultural activities prevalent in these regions.
- Examine farm distribution in Gauteng province, focusing on the number of farms and their primary produce categories, including crop and animal production metrics.

### Data Collection
The data for this analysis was sourced from the  South Africa Agricultural statistics platforms, specifically from the [Department of Agriculture, Land Reform & Rural Development](https://wwww.dalrrd.gov.za). The datasets include:
- Farm Distribution by Province Data: This dataset provides information on the distribution of farms across South Africa's provinces.
- Crop Production Data: Focused on crop yields and production within the Gauteng province.
- Animal Production Data: Contains detailed records of animal produce across the regions.
- Value Chain Data: Highlights the value chain processes for various agricultural produce.
These datasets formed the foundation for analyzing agricultural patterns and trends across the country.

### Tool
The data cleaning, analysis and visualization was done using Excel

### Preprocessing 
After downloading and opening the data in Excel, several steps were taken to ensure it was ready for analysis, therefore, the following actions were carried out:
- Duplicate check: No duplicate rows were found in the dataset.
- Data type check: The columns were reviewed to ensure they were assigned the appropriate data types. Where necessary, columns were converted to text or numbers.
- Missing values: Missing values where checked across the rows in the data set but none were found. The dataset was free from null values which makes it accurate to proceed for the  analysis.
- Categorical variables: All categorical variables were inspected for spelling errors or unexpected values. No issues were found.
- Outliers: No outliers were detected in the dataset.

### Exploratory Data Analysis
I analyzed the dataset to understand its structure, identify key patterns, and uncover valuable insights. It was important to determine the total distribution of farms across provinces in South Africa and evaluating the gross margin for various distribution channels. Additionally, I discovered two key agricultural contexts in Gauteng province: crop production and animal production.

### Insights

1. **Distribution of Farms According to Provinces:** The Free State has the highest number of farms, with 7,951 farms, indicating it is a major agricultural hub. Gauteng on the other 
   hand has the lowest number of farms at 2,291, likely due to its urbanized nature and smaller land area dedicated to agriculture. There is a noticeable disparity between provinces, 
   with the Free State having over three times the farms compared to Gauteng. This highlights the diverse agricultural focus across South Africa's provinces. Provinces with larger land 
   areas (e.g, Free State, Northern Cape, and Western Cape) tend to have higher farm distributions.
   This indicates a strong correlation between land availability and farm numbers. Provinces like Gauteng, with high urbanization, have the lowest farm counts, while rural provinces like 
   Free State dominate, showing an inverse relationship between urbanization and farm distribution.


   ![image](https://github.com/user-attachments/assets/e119ec82-960a-4bd4-828e-5077ac27dd2b)

2. **Gross Margin for Distribution Channels:** The chart illustrates the percentage contribution of gross margin among four different stakeholders in the distribution channel:
   Farmers, Wholesalers, Distributors, and Retailers. Farmers hold the largest share of the gross margin at 30%, which means that they capture the highest proportion of revenue within 
   the distribution chain. This might reflect the value of primary production in the supply chain. Both Retailers and Distributors contribute equally at 25% of the gross margin.
   As such, it indicates a balanced distribution of profits between these two intermediary roles. Wholesalers account for only 20%, the smallest gross margin share. This might indicate 
   that wholesalers operate with narrower profit margins or focus on high-volume sales rather than high profit per unit.

   ![image](https://github.com/user-attachments/assets/044d7f75-e344-444f-a2c7-f52c93b0aff0)

3.  **Crop Production:** Grain/Cereal is the highest produced crop with a significant volume of 425,857 units. This highlights its importance in Gauteng's agricultutal sector,
   likely driven by its role as a staple food and input for other agricultural processes. Maize follows closely as the second-largest crop with 416,719 units, just slightly behind Grain/    Cereal. This indicates a focus on maize, which is a critical crop for food security, animal feed, and industrial purposes. The production volumes drop substantially for Oil Seed     26,609 units, Soya Beans 22,501 units, Cabbage 10,901 units, and Vegetables 9,494 units which is the lowest crop production. These crops may cater to specific markets, smaller demand, or specialized agricultural practices.

    ![image](https://github.com/user-attachments/assets/dd149e04-72bb-45fb-bf83-b44f96d8746f)

4.  **Animal Production:** The bar chart shows the top 10 animal production outputs in Gauteng, measured by quantity. Cattle has the highest production with 677,769 units, making it the dominant livestock category in Gauteng. This indicates the importance of cattle farming for meat, dairy, or other economic purposes, also indicates a focus on large-scale livestock farming for food products like beef and pork.
Pig production is the second-largest with 511,688 units, showing its importance as a key source of meat production in the region. Cattle and Pig production dominate the animal production sector. The Chicken Layers 791 units, Milk and Cream 580 units, Bull 503 units, Springbok 450 units, and Goat 327 units shows the lower small scale livestock production. It is clearly seen that goat is the least with 327 units. These are likely serving small markets or being region-specific livestock.

    ![image](https://github.com/user-attachments/assets/a27bc83d-6657-4f2d-91a9-1e3243f6e163)

### Dashboard

![Screenshot 2024-12-16 133334](https://github.com/user-attachments/assets/2aac25a9-cb25-4f49-9cf9-a586802f5529)

### Recommendation
  Following a comprehensive analysis of the data, the following recommendations are proposed to ensure there is an improve in sale and operations of Earth To Home Company
1.  Grain/Cereal and Maize are the most produced crops in Gauteng, therefore it is essential to prioritize investment in these crops for large-scale production and distribution as they are essential commodities with consistent demand.
2.  By encouraging and facilitating access to modern irrigation systems (e.g., drip irrigation, automated systems), Earth to Home can improve productivity for partnered farmers in its supply chain. This will ensures a consistent supply of crops such as maize, cereals, and vegetables, which are critical to the company’s operations and downstream distribution.
3.  Earth to Home can partner with agricultural research institutes or seed companies to provide high-yield and disease-resistant seeds to farmers in their network. This will ensure farmers have access to better-quality inputs, the company can improve the quantity and quality of produce sourced for distribution.
4.  It is important to play an active role in helping farmers access financial tools such as subsidies, grants, or affordable credit. Farmers will have the financial capacity to adopt better tools, such as irrigation systems and quality inputs, and it will also ensure increased production of crops and animal products, securing Earth to Home’s supply chain.
5.  A robust monitoring and evaluation framework should be established to monitor production, distribution, and margins to identify opportunities and track performance. To ensure the success and sustainability of the Earth to Home Project, stakeholders should be actively engaged through ongoing dialogue and feedback mechanisms to promote accountability and transparency.






