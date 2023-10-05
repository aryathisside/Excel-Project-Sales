# Excel-Project-Sales
"This project encompasses a range of functionalities, including data cleaning, data processing, and comprehensive data analysis."

Excel Dataset Download (direct): https://bit.ly/3X381ok

**Sample questions:**
1. Compare sales and orders using a unified chart.
2. Determine the month with the highest sales and order numbers.
3. Analyze the gender-based purchasing patterns in 2023 to identify if more purchases were made by men or women.
4. List the various order statuses observed in 2023.
5. Compile a list of the top 10 states that have significantly contributed to the sales.
6. Explore the correlation between age and gender concerning the number of orders placed.Identify the sales channel that has made the most significant contribution.
7. Determine the highest-selling product category.
8. Determine the highest-selling product category.

**Steps**
1. **Data cleaning** 
-> Checking each column systematically to identify any null values in the dataset.
-> **Problem & solution**
  1. Problem : - Four entries are labeled as "mens" and "womens."
     Solution: -  Replaced "m" with "men" and "w" with "women."
  2. Problem:- Data contains entries such as 1, 2, 3, 4, 5, "one," "two."
     Solution:- Replaced "one" with 1 and "two" with 2. 
   3. Problem:-  Incorrect spelling for "amazon," "meesho," and "myntra."
     Solution:- Replaced the misspelled entries with the correct ones.
2. **Data processing **
	Adding a new column to categorize age groups using the formula:
		=IF(E2 >= "senior", IF(E2 >= "Adult", "Teenager"))
	-> Adding a new column to extract the month to address problem 2 using the formula:
		=TEXT(G2, "mmm") returns "dec" / =TEXT(G2, "mmmm") returns "december"

**Sample Insights** 
1. Maharashtra, Karnataka, and Uttar Pradesh are the top three states, accounting for approximately 35% of the total.
2. Women demonstrate a higher purchasing propensity compared to men, constituting about 64% of the customer base.
3. The age group of adults ranging from 30 to 49 years is the primary contributor, making up approximately 50% of the consumer base.
4. Sales are predominantly driven through Amazon, Flipkart, and Myntra channels, contributing around 80% to the overall sales.
 
**Final conclusion**
-> Target female customers within the age group of 30-49 years residing in Maharashtra, Karnataka, and Uttar Pradesh by strategically presenting advertisements, offers, and coupons available on Amazon, Flipkart, and Myntra platforms.

