# 📦 Marketplace Health & Logistics Optimizer
Power BI Marketplace Health project analyzing e-commerce orders at brazil

## Data Used
<a href="https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce">Marketplace Health E-Commerce</a>
</br>
Used under a public data license for educational purposes.

## Dasboard
<a href="https://app.powerbi.com/groups/bf032d05-b0dc-4419-a61f-001fbda50240/dashboards/81d80bc3-d436-47fe-a645-40f2cf7d1051?experience=power-bi">Marketplace Health & Logistics Optimizer</a>
</br>

## 📊 Project Overview
This project analyzes the operational health of a major Brazilian E-commerce marketplace (Olist), managing a complex dataset of 99.5K orders across a vast geographic landscape. Despite high transaction volumes, the marketplace faced a critical 21.24% cancellation rate, leading to a staggering 24% revenue leakage (approximately $3.5M in lost cost).

## 🧩 Business Task
The marketplace operator aims to analyze e-commerce transaction and logistics data to identify where and how order cancellations and revenue leakage are concentrated across different product categories, seller performance, and shipping routes.

## 🧰 Tools Used
Python - Pandas & NumPy, NLTK / VADER, 
</br>
SQL - Data Cleaning & Standardisation:, Integrity Management, Complex Joins
</br>
Power BI – Power Query (ETL), Data modeling, DAX measures, dashboards.
</br>
PowerPoint → Final presentation of insights and recommendations.

## 🧹 Data Cleaning
Handled missing values and orphans.
</br>
Optimized model relationships.
</br>
Standardized formats and data types.
</br>
Engineered logistical metrics.
</br>
Filtered noise and outliers.


## 📈 Key Insights
A significant 21% of orders are cancelled, resulting in a 24% loss of potential revenue ($3.5M). These cancellations are primarily driven by high shipping costs and extended lead times..
</br>
São Paulo (SP) leads in total cancellations with 7.6K failed orders, while Paraná (PR) experiences the most severe delays with an average of 12.4 days..
</br>
The Top 5 sellers account for 1,492 cancellations, with an average waiting time of 12.5 days—significantly higher than the platform average..
</br>
Shipping costs account for 18% of total transaction value ($19.13 avg). Data confirms that as shipping costs increase, review scores decrease, which negatively impacts high-value customer retention..
![](https://github.com/Omer-mohamed01/olist-ecommerce/blob/44ccff7936e197b96bf40fc9a7b21a1092135fb2/Charts/Average%20of%20Shipping%20cost%20by%20Order%20waiting%20level.png)
</br>
![](https://github.com/Omer-mohamed01/olist-ecommerce/blob/44ccff7936e197b96bf40fc9a7b21a1092135fb2/Charts/Relation%20Between%20Review%20Score%20and%20Shipping%20Cost.png)

## 💡 Recommendations
Implement a "Shipping Subsidy" or "Fulfillment Speed-Up" initiative to prevent order abandonment and recover lost costs..
</br>
Prioritize the top 5 states for logistics infrastructure improvements, focusing specifically on enhancing carrier service quality in SP and PR..
</br>
Conduct a performance audit for these top 5 sellers to streamline their internal dispatch processes and reduce initial processing delays..
</br>
Optimize shipping fee structures; lowering costs for the customer correlates directly with higher review scores and increased total transaction volume..


## 🧠 Outcome
This analysis provided clear, actionable insights into the factors influencing e-commerce marketplace fulfillment and revenue retention. Key outcomes include the identification of the 8.5-day "Last-Mile" bottleneck and the quantification of $3.5M in at-risk revenue due to high cancellation rates.
</br>
The project translates complex logistics and customer sentiment data into a practical strategic roadmap that supports improved operational efficiency, carrier performance management, and data-driven revenue recovery.

---

## 🗂️ Project Structure


Healthcare Operations
</br>
README.md
</br>
LICENSE
</br>
├── Data |
    └──<a href="https://github.com/Omer-mohamed01/olist-ecommerce/tree/main/Data%20Source">Data Source.csv</a>
    </br>
├── Link |
    └──<a href="https://github.com/Omer-mohamed01/olist-ecommerce/blob/main/Data%20Source/Data%20Source%20Link.txt">Data Source Link.txt</a>
</br>
├── Business Task |
    └──<a href="https://github.com/Omer-mohamed01/olist-ecommerce/blob/main/Business%20Task/Business%20Task.txt">Business Task.txt</a>
</br>
├── Excel |
  └──<a href="https://github.com/Omer-mohamed01/olist-ecommerce/tree/main/Data%20Cleaning">Data Cleaning.xlsx</a>
</br>
├── Presentation |
   └── <a href="https://github.com/Omer-mohamed01/olist-ecommerce/blob/main/Document/Marketplace%20Health%20%26%20Logistics%20Optimizer.pdf">Medical Appointment 2016.pdf</a>
</br>
├── Images |
   └── <a href="https://github.com/Omer-mohamed01/olist-ecommerce/tree/main/Charts">Charts.png</a>

---

## 🧠 Explanation
This structure helps others quickly understand:
- What each folder contains  
- How your project is organized  
- Where to find key deliverables (data, presentation, visuals)

---

