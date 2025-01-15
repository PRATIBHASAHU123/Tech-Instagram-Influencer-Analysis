Tech Instagram Influencer Analysis
--------------------------------------

Project Overview
---------------------------

This project involves analyzing Instagram activity data related to tech influencers. The main objective is to explore patterns, answer business-related questions, and derive actionable insights using SQL queries.

Problem Statement
---------------------

Analyze database tables containing Instagram activity data to identify trends, answer key business questions, and extract meaningful insights.

Dataset
---------------

The dataset used in this project is stored in the gdb0120 database and comprises the following tables:

dim_date: Contains date-related information.

fact_account: Stores account activity details.

fact_content: Includes content-related metrics.

Key Objectives
---------------------

The project aims to address the following ad-hoc requests:

Identify unique post types: Determine the number and types of posts in the fact_content table.

Impressions analysis: Identify the highest and lowest impressions for each post type.

Weekend post filtering: Extract posts published on weekends in March and April and export them to a CSV file.

Account statistics report: Generate a report with total profile visits and new followers per month.

Likes by category in July: Calculate the total likes for each post category in July, arranged in descending order.

Monthly post category counts: Display unique post categories and their counts per month.

Reach percentage breakdown: Analyze the percentage of total reach for each post type.

Quarterly engagement metrics: Report total comments and saves for each post category grouped by quarters (Q1, Q2, Q3).

Top follower dates: List the top three dates in each month with the highest number of new followers.

Weekly shares report: Create a stored procedure to calculate total shares for each post type by week.

Highlights from Analysis
--------------------------

Post Types: Four distinct post types (IG Video, IG Image, IG Carousel, IG Reel) were identified.

Impressions:

IG Reels perform best with the highest impressions.

IG Carousels have the lowest impressions.

Reach:

IG Reels dominate with 61.63% of the total reach.

IG Carousels contribute the least (0.69%).

Engagement:

"Tech Tips" posts lead in comments and saves during Q2 and Q3.

"Mobile" posts maintain consistent engagement.

Tools and Technologies
------------------------------

SQL: For querying the dataset and generating insights.

Excel:For making charts
