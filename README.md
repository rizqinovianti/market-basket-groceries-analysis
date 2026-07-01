# 🛒 Market Basket Analysis using Python \& Power BI

### 

### Project Overview



This project aims to analyze customer purchasing patterns using \*\*Market Basket Analysis (MBA)\*\* and build an interactive dashboard using \*\*Power BI\*\*.



The analysis was conducted on \*\*14,963 transactions\*\* consisting of \*\*167 product types\*\* to determine:



* Customer transaction characteristics
* Most frequently purchased products
* Purchasing patterns based on the number of products (Basket Size)
* Relations between products using the \*\*Apriori\*\* algorithm
* Association Rules as a foundation for evaluating bundling strategies





### Dataset Information



| Information | Value |

|-------------|------:|

| Total Transactions | \*\*14,963\*\* |

| Total Customers | \*\*3,898\*\* |

| Total Products | \*\*167\*\* |

| Analysis Method | Market Basket Analysis (Apriori) |





### Project Objectives



* Conduct exploration of customer transaction patterns.
* Identify products with the highest purchase frequency.
* Analyze customer Basket Size.
* Find frequent itemsets using the Apriori algorithm.
* Generate Association Rules to evaluate product bundling opportunities.
* Present analysis results through an interactive dashboard in Power BI.



### Tools



* Python



Libraries used:



* pandas
* numpy
* matplotlib
* seaborn
* mlxtend

&#x20; - TransactionEncoder

&#x20; - apriori

&#x20; - association\_rules



* Microsoft Power BI



### Project Structure



```

Market-Basket-Analysis/

│

├── Dataset/

│   ├── groceries.csv

│

├── Notebook/

│   ├── Data\_Cleansing.ipynb

│   ├── Exploratory\_Data\_Analysis.ipynb

│   ├── Market\_Basket\_Analysis.ipynb

│

├── Power BI/

│   ├── Market Basket Analysis.pbix

│

├── Dashboard/

│   ├── Dashboard\_1.png

│   ├── Dashboard\_2.png

│   ├── Dashboard\_3.png

│

├── README.md





### Analysis Workflow



1\. Data Cleaning



* Missing value checking
* Duplicate checking
* Feature engineering
* Basket Size calculation
* Transaction grouping



2\. Exploratory Data Analysis (EDA)



* Product distribution
* Basket Size distribution
* Daily transaction analysis
* Monthly transaction analysis



3\. Market Basket Analysis



* Transaction Encoding
* Frequent Itemsets (Apriori)
* Association Rules
* Support
* Confidence
* Lift



4\. Dashboard Development



The dashboard was developed using Power BI and consists of:



* Dashboard 1

Customer Transaction Overview



\- Total Transactions

\- Total Customers

\- Median Basket Size

\- Basket Size Distribution

\- Daily Transactions

\- Monthly Transactions



* Dashboard 2

Top Selling Products



\- Treemap Product Composition

\- Top 5 Most Purchased Products



* Dashboard 3

Association Rules Analysis



\- Total Frequent Itemsets

\- Total Association Rules

\- Association Rules Table

\- Lift Comparison Chart



### Key Findings



* The dataset consists of **14,963 transactions** and **167 product types**.
* The majority of customers purchased **2 products per transaction (67.37%)**.
* The most frequently purchased product is **Whole Milk (2,502 transactions)**.
* **69 Frequent Itemsets** were found.
* **10 Association Rules** were generated.
* The highest Lift value is only **0.82**, indicating that there is no strong enough relationship between products to support a bundling strategy yet.



### Business Recommendations



1. Focus promotions on products with the highest demand.
2. Increase Basket Size through additional purchase promotions.
3. Avoid implementing permanent bundling since the Lift value is still below 1.
4. Collect more comprehensive transaction data for further analysis.





### Author



**Rizqi Novianti**



Aspiring Data Analyst | Business Analysis | Data Visualization | Business Intelligence



