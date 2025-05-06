# DataCamp-Analyzing-Unicorn-Companies
My work for a DataCamp project to analyze unicorn companies of different industries. This project aims to gain insight regarding industries with emerging unicorn companies and the industry valuation from the given dataset. I applied table joining, filtering, and grouping to understand industries with high-growth companies.

## Description
An investment firm wants to understand companies and industries who are producing the highest valuations and the rate at which these companies are emerging in each industry from the given data. The goal is to show the top 3 industries with the highest average valuation based on emerging unicorn companies of recent years.

## Dataset
The dataset consists of four tables from the Unicorn database, showing company and industry information, as well as funding and relevant dates for companies.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c575fb41-e658-47b8-93e9-315518d5138f">
</p>
<p align="center">Figure 1. Data dictionary for 'industries' table.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7260c27c-8e37-4e8e-b121-bad3f07dfe81">
</p>
<p align="center">Figure 2. Data dictionary for 'companies' table.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8f5bc112-4477-4659-8baa-f76d4d7154bb">
</p>
<p align="center">Figure 3. Data dictionary for 'dates' table.</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/572e32cc-5f00-4785-bc46-806c7a0cb4d6">
</p>
<p align="center">Figure 4. Data dictionary for 'funding' table.</p>

## Walkthrough

### 1. Top 3 Industries

<p align="center">
  <img src="https://github.com/user-attachments/assets/ae22a02a-2a60-4f3d-87ef-f5802f8ca882">
</p>
<p align="center">Figure 5. SQL query to find relevant unicorn companies.</p>
<p align="center">Firstly, I find companies who become unicorns in the given range of years, as well as their industry and valuation which will be relevant in the next step.</p> <br><br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d0baf1bd-0cc5-45da-b745-138e5529949f">
</p>
<p align="center">Figure 6. SQL query to find top 3 industries based on valuation of unicorn companies.</p>
<p align="center">Next, from the step above I grouped the valuation of each company based on industry and return the top 3 industries with most valuations.</p> <br><br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c6e897c3-cf37-4991-bc14-2315eb9d59fb">
</p>
<p align="center">Figure 7. SQL query to find top 3 industries based on valuation of unicorn companies.</p>
<p align="center">Lastly, I displayed the amount of unicorn companies in each year for each industry and the average industry valuation by joining the previous two queries with the 'industry' table. </p> <br><br>

![image](https://github.com/user-attachments/assets/78bea770-0bf3-4454-af1a-c6bcd6475c8b)
<p align="center">Figure 8. Top 3 industries based on unicorn company valuation for year 2019 - 2021.</p>

## Conclusion
This project shows my ability to join tables, filter data, and group results to uncover key insights. I identified top industries by unicorn count and valuation across multiple years, demonstrating strong SQL and analytical skills.
