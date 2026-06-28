# database-programming-assignmentt
31086-2025
# Database Programming Assignment: Sales Management System
**Student Name:** Mutaz Aboud Khamis
**Student ID:** 31086/2025
**Course Title:** C11665 - DPR400210: Database Programming
**Submission Date:** June 29, 2026
## 1. Business Problem
In the modern retail environment, data-driven decision-making is essential. This project aims to address the challenges of tracking customer transactions, inventory levels, and product performance. By implementing a relational database, we can effectively manage sales operations, provide insights into customer behavior, and optimize inventory management.
## 2. Database Schema & ER Diagram
The database is structured around three core related tables: **Customers**, **Products**, and **Orders**. This relational design ensures data integrity through the use of Primary Keys and Foreign Keys, establishing a 1:N relationship structure where a single customer can place multiple orders, and a product can be featured in numerous transactions.
*(Note: Refer to ER_Diagram.png for the detailed visual representation).*
## 3. CTE Implementations
Common Table Expressions (CTEs) were utilized to enhance query readability and complexity management:
 * **Simple CTE:** Used for basic filtering of customer data.
 * **Multiple CTEs:** Implemented for multi-stage processing of order history.
 * **Recursive CTE:** Applied to analyze hierarchical product categories or organizational structures.
 * **CTE with Aggregation:** Used to calculate total sales per product.
 * **CTE combined with JOINs:** Applied to combine customer profiles with their specific transaction records.
## 4. SQL Window Functions
Window functions were implemented to perform advanced analytical tasks:
 * **Ranking Functions:** Utilized ROW_NUMBER(), RANK(), DENSE_RANK(), and PERCENT_RANK() to prioritize top-performing products.
 * **Aggregate Window Functions:** Applied SUM() OVER() and AVG() OVER() to track cumulative sales trends.
 * **Navigation Functions:** Used LAG() and LEAD() to compare current order values against previous transactions.
 * **Distribution Functions:** Employed NTILE() and CUME_DIST() for market segmentation analysis.
## 5. Analysis and Findings
 * **Descriptive Analysis:** The system tracks what occurred regarding historical sales volumes and customer purchasing trends.
 * **Diagnostic Analysis:** By analyzing the patterns in Orders, we identify why certain products experience peak demand periods.
 * **Prescriptive Analysis:** Based on these findings, management should focus on stocking high-performing products and offering personalized promotions to frequent customers.
## 6. Academic Integrity Statement
I, Mutaz Aboud Khamis (ID: 31086/2025), hereby declare that this project is my original work. I have adhered to all university regulations regarding academic integrity, and this assignment has not been copied from any classmate or online repository.
