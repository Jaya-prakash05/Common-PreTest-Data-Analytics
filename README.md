SECTION A: DATA ANALYSIS & SCIENCE
1. Handling Missing Values in Age Column
Before analysis, I would first understand why the age values are missing and check if the missing data is random. Since only 15% of values are missing, I would handle it by filling them using the median age, as it is less affected by outliers. If age plays a major role, I may also group similar customers and fill values accordingly. After handling, I would verify results using summary statistics and visualizations.
2. Identifying Frequently Purchased Products
This problem can be solved using Market Basket Analysis. I would apply association rule mining techniques such as the Apriori or FP-Growth algorithm. Metrics like support, confidence, and lift help identify strong product combinations. Python libraries like mlxtend and SQL for data preparation would be useful.
3. Bar Chart vs Histogram
A bar chart is used to represent categorical data such as product categories or regions.
A histogram is used for continuous numerical data like age or income.
Bar charts show comparisons between categories, while histograms show data distribution and patterns.
4. SQL Query
SELECT customer_id, SUM(amount) AS total_spent
FROM purchases
WHERE city = 'New York'
  AND purchase_date BETWEEN '2024-01-01' AND '2024-01-31'
GROUP BY customer_id
HAVING SUM(amount) > 500
ORDER BY total_spent DESC;
5. Increased Page Load Time with High Traffic
Possible reasons:
Server resource limitations (CPU/RAM)
Slow database queries or high query volume
Network bandwidth constraints
To investigate further, I would monitor server metrics, analyze database performance, and conduct load testing to identify bottlenecks.

SECTION G: TECHNICAL MINDSET & PROBLEM SOLVING 
1. Learning a New Technical Skill
I start by understanding the overall concept and real-world use cases. Then I learn the basics from documentation or tutorials and practice with small examples. Building a mini project helps reinforce learning. I know I’ve understood it when I can apply it independently.
2. When Stuck on a Technical Problem
I break the problem into smaller parts, carefully analyze error messages, refer to documentation, and search trusted resources. Taking short breaks and explaining the problem to someone else also helps gain clarity.
3. Explaining Technical Concepts to Non-Technical People
For example, a database can be explained as a digital cupboard where information is stored neatly so it can be accessed quickly whenever needed.
4. Meaning of Debugging
Debugging is not just fixing errors but understanding the system’s behavior, identifying where it deviates from expectations, and solving issues systematically using logical reasoning.
5. Importance of Documentation
Documentation helps in understanding the project later, maintaining consistency, reducing errors, and saving time. Even for personal projects, it acts as a reference and improves clarity.
Conclusion
This assessment reflects my current understanding, logical thinking, and problem-solving approach. It represents an honest effort to demonstrate foundational technical knowledge and learning ability.
