![Edu Capstone 3a Dashboard](https://github.com/EduBassey/Global-superstore-analysis/assets/170472577/a376f5ac-64cc-481e-b777-dc8a04f7067e)![Edu Capstone 3a Dashboard](https://github.com/EduBassey/Global-superstore-analysis/assets/170472577/8ef9d73a-10fb-4f3e-a598-633ae9fdc4e4)

# Global superstore analysis

### Project overview

Global Superstore is a global online retailer based in New York, boasting a broad product catalog and
aiming to be a one-stop-shop for its customers. Global The superstore’s clientele, hailing from 147
different countries, can browse through an endless offering with more than 10,000 products. This large
selection comprises three main categories: office supplies (e.g., staples), furniture (e.g., chairs), and
technology (e.g., smartphones).
You are contracted as a Data Analyst to help Global Superstore analyze and draw out meaningful insight
from the Superstore dataset which would aid management in making informed decisions to improve
performance.

![Edu Capstone 3a Dashboard](https://github.com/EduBassey/Global-superstore-analysis/assets/170472577/f7b1cf83-f4df-4d71-9050-db3c91f854d2)

![Edu Capstone 3b Dashboard](https://github.com/EduBassey/Global-superstore-analysis/assets/170472577/182f538c-f5d8-4caa-8ec9-73280412a910)


### Data sources

The primary datset for this analysis is provided in this link: https://docs.google.com/spreadsheets/d/1nxESpFzWjlGDMGDVLH69xmDzIl9l6OEq/edit#gid=633280281 which is a spreadsheet containing infomation about the globalsuperstore sales.

### Tools
- Excel - data cleaning
- powerbi - data analysis, data visualization

### Data cleaning/analysis
  1. power query editor was used to clean the data and remove duplicates
  2. DAX operator was used to perform calculation
  3. data modelling to merge and form relationship between fields

  ### Exploratory Data analysis
  Question 1.
a) What are the three countries that generated the highest total profit for Global Superstore in 2014?
b) For each of these three countries, find the three products with the highest total profit. Specifically,
what are the products’ names and the total profit for each product?

Question 2.
a) Identify the 3 subcategories with the highest average shipping cost in the United States.

Question 3.
a) Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African
countries?

b) What factors might be responsible for Nigeria’s poor performance? You might want to investigate
shipping costs and the average discount as potential root causes.

Question 4.
a) Identify the product subcategory that is the least profitable in Southeast Asia.
Note: For this question, assume that Southeast Asia comprises Cambodia, Indonesia, Malaysia, Myanmar
(Burma), the Philippines, Singapore, Thailand, and Vietnam.
b) Is there a specific country i n Southeast Asia where Global Superstore should stop offering the
subcategory identified in 4a?

Question 5.
a) Which city is the least profitable (in terms of average profit) in the United States? For this analysis,
discard the cities with less than 10 Orders. b) Why is this city’s average profit so low?

Question 6.
a) Which product subcategory has the highest average profit in Australia?


Question 7.
a)Who are the most valuable customers and what do they purchase?

### Data Analysis
The DAX function was used to perform interesting calculations similar to that of Excel
```DAX
CALCULATE (SUM(Orders[sales]),FILTER(Orders,order[country]="united states"))


### Results

1.United States had the highest profit, followed by India and China.
b. United states-Canon Image Class 2200 advanced copier
India-Sauder classic bookcase, traditional
China-Sauder classic bookcase metal

question 2 : sub categories with highest shipping cost- Chairs followed by Phone and storage

question 3 Nigeria's profit was low compared to other African countries, one factor why it was low
because of the high discount rate

question 4.least subcategory product in south east Asia- Tables
the superstore should stop offering Indonesia tables

question 5: Lancester is the least profitable city
the average is low because there are few customers in the city

question 6: Copiers has the highest average profit in Australia

question 7:Tamara Chand is the most valuable customer, followed by Raymond Buch and Sanjit Chand








