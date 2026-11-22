# the-billionaire-wealth-investigation
# 💰 The Billionaire Wealth Investigation
### SQL Data Analysis Project

**Author:** Kgothatso Makgalemane 
**Programme:** FadaQa Tech Scholarship Program (FSP 2.0) – Data Analysis Track  
**Project Category:** Data Analytics  
**Database:** SQLite  

---

## 1. Project Overview

The Billionaire Wealth Investigation is an SQL-based data analysis project that explores wealth distribution among the world's 200 richest individuals, according to the Forbes list.

Acting as a Junior Data Analyst for a global financial research organisation, the objective of this project is to investigate financial and demographic patterns among the world's wealthiest individuals.

Using SQL and SQLite, the analysis explores billionaire net worth, age demographics, geographical distribution, and industry representation to identify meaningful patterns and insights.

## 2. Business Scenario

A global financial research organisation wants to understand how wealth is distributed among the world's 200 richest people.

The organisation requires an analysis of the dataset to identify:

- The wealthiest individuals.
- Age patterns among billionaires.
- Countries with the highest billionaire representation.
- Industries with the greatest number of billionaires.
- The distribution of billionaire wealth across different countries and industries.

The analysis uses SQL queries to extract, organise, and interpret relevant information from the dataset.

## 3. Dataset Description

The project uses the **Top 200 Richest Person in the World Dataset**, which contains financial and demographic information about 200 of the world's wealthiest individuals.

### Dataset Columns

| Column | Description |
|---|---|
| Serial Number | Sequential numbering of the billionaires. |
| Rank | Global ranking based on net worth. |
| Name | Name of the billionaire. |
| Age | Age of the billionaire. |
| Country | Country associated with the billionaire. |
| Net Worth | Total net worth expressed in billions of US dollars. |
| Industry | Primary industry associated with the billionaire's wealth. |

**Dataset size:** 200 records and 7 columns.

## 4. Tools and Technologies

The following tools and technologies were used:

- **SQLite:** Database management and SQL query execution.
- **SQL:** Data extraction, filtering, sorting, aggregation, and analysis.
- **GitHub:** Project hosting, documentation, and version control.
- **CSV:** Dataset storage and query result exports.

## 5. Data Exploration

Before answering the business questions, preliminary queries were performed to understand the dataset.

The exploration included:

1. Retrieving the entire dataset.
2. Selecting billionaire names, ages, and net worths.
3. Retrieving the first 10 billionaires in the dataset.
4. Identifying all unique countries represented.
5. Identifying all unique industries represented.

These queries provided an initial understanding of the dataset and its structure.

## 6. Business Questions

The following 10 business questions were investigated using SQL:

| No. | Business Question |
|---|---|
| 1 | Who are the 20 richest billionaires? |
| 2 | Who are the five youngest billionaires? |
| 3 | What are the average age and average net worth of the billionaires? |
| 4 | Which five countries have the highest billionaire representation? |
| 5 | What is the combined net worth of billionaires from each country? |
| 6 | Which five industries have the highest number of billionaires? |
| 7 | Which countries have at least five billionaires? |
| 8 | What is the total wealth of billionaires younger than 50? |
| 9 | Which billionaires have a net worth exceeding the overall average? |
| 10 | Which industry has the highest average net worth? |

## 7. SQL Concepts Applied

The project demonstrates the practical application of the following SQL concepts:

| SQL Concept | Application |
|---|---|
| SELECT | Retrieving specific columns and records. |
| DISTINCT | Identifying unique values. |
| WHERE | Filtering records based on conditions. |
| ORDER BY | Sorting query results. |
| ASC and DESC | Sorting data in ascending and descending order. |
| LIMIT | Restricting the number of returned records. |
| GROUP BY | Grouping records for analysis. |
| COUNT() | Counting records within groups. |
| SUM() | Calculating combined net worth. |
| AVG() | Calculating average age and net worth. |
| HAVING | Filtering grouped results. |
| ROUND() | Rounding numerical results. |
| Subqueries | Comparing individual net worth against the overall average. |

## 8. Key Findings and Insights

The analysis produced several interesting findings about wealth distribution among the 200 billionaires.

### 8.1 Age and Wealth

- The average age of billionaires in the dataset is **69.38 years**.
- The average net worth is approximately **$31.84 billion**.
- There are **16 billionaires younger than 50**.
- Billionaires younger than 50 collectively hold approximately **$508.3 billion** in wealth.

### 8.2 Geographical Distribution

The United States has the highest representation in the dataset.

| Country | Number of Billionaires |
|---|---:|
| United States | 79 |
| China | 16 |
| India | 13 |
| Germany | 11 |
| Russia | 11 |

The United States accounts for a substantial proportion of the individuals represented in the dataset.

### 8.3 Industry Representation

Technology is the most represented industry, followed by Finance & Investments.

| Industry | Number of Billionaires |
|---|---:|
| Technology | 40 |
| Finance & Investments | 32 |
| Fashion & Retail | 30 |
| Diversified | 15 |
| Food & Beverage | 15 |

### 8.4 Wealth Distribution Across Industries

Telecom has the highest average billionaire net worth at approximately **$102 billion**.

However, this industry is represented by only one billionaire in the dataset.

This demonstrates why average values should be interpreted alongside the number of records in each category.

### 8.5 Wealth Above the Average

The analysis identified **53 billionaires** whose individual net worth exceeds the overall average net worth of approximately $31.84 billion.

## 9. Recommendations

Based on the findings, the following areas could be explored further:

1. Investigate why certain countries have significantly higher billionaire representation than others.
2. Examine the industries that contribute most significantly to billionaire wealth.
3. Explore the relationship between age and accumulated wealth.
4. Investigate industries with high average net worth but relatively few billionaire representatives.
5. Conduct further research into geographical and industry-related wealth concentration.

## 10. Conclusion

The Billionaire Wealth Investigation demonstrates how SQL can be applied to real-world financial datasets to answer business questions and uncover meaningful insights.

Through data exploration, filtering, sorting, grouping, and aggregation, the project provides an overview of wealth distribution among the world's 200 richest individuals.

The findings highlight the dominance of the United States in billionaire representation, the significant presence of the technology industry, and the differences in wealth distribution across industries.

This project strengthened my understanding of SQL and its practical application in data analytics, particularly in transforming raw data into meaningful information that can support informed decision-making.

## 11. Repository Structure

The project is organised as follows:

```text
Billionaire_Wealth_Investigation/
│
├── README.md
│
├── Top_200_Richest_People.csv
│
├── Billionaire_Wealth_Investigation.sql
│
└── Results/
    │
    ├── query_1_results.csv
    ├── query_2_results.csv
    ├── query_3_results.csv
    ├── query_4_results.csv
    ├── query_5_results.csv
    ├── query_6_results.csv
    ├── query_7_results.csv
    ├── query_8_results.csv
    ├── query_9_results.csv
    └── query_10_results.csv
```

---

**Project:** The Billionaire Wealth Investigation  
**Technology:** SQL | SQLite  
**Programme:** FadaQa Tech Scholarship Program (FSP 2.0)  
**Focus:** Data Analysis and Business Intelligence
