# INSTA_USER_ENGAGEMENT-SQL-PROJECT-

📸 Instagram User Engagement Analysis
This project simulates a backend database and analytics environment for an Instagram-like social media platform. It is designed to analyze user behavior, content performance, and engagement metrics using SQL and Power BI.

The project demonstrates how to structure a relational database, populate it with realistic mock data, and build business intelligence views and dashboards for insight-driven decision making.

🧱 Project Features
Database Design: Created a normalized relational schema (ig_clone) with tables for users, photos, likes, comments, follows, tags, and photo-tags junction.

Mock Data Population: Inserted large-scale, realistic data entries (e.g., 100 users, 200+ photos, thousands of likes and follows) using SQL insert scripts.

Business Logic via SQL Views: Designed and implemented analytical views like:

user_photo_summary: Number of photos per user

most_followed_users: Follower count per user

photo_likes_count: Total likes per photo

user_engagement: Combined user metrics (posts, likes, followers)

📊 Power BI Dashboard
Live Connection to MySQL: Connected Power BI to the SQL database using the DirectQuery mode.

Visualizations Built:

Bar charts: Top content creators and most followed users

Pie charts: Distribution of photos per user

Tables: Detailed user engagement matrix

Slicers and filters: Dynamic exploration by username and metrics

KPI Insights: Identified power users, peak content activity, and high-performing content.

🔧 Tools & Technologies
Database: MySQL

Analytics: Power BI

Language: SQL (MySQL dialect)

Platform: Power BI Desktop + Local SQL Server / MySQL instance

📁 Folder Structure (Suggested)
pgsql
Copy
Edit
/sql/
  - create_tables.sql
  - insert_data.sql
  - views.sql

/powerbi/
  - Instagram_User_Engagement.pbix

/README.md
🚀 Outcomes
Demonstrated ability to model social media interaction data using SQL.

Built real-time BI dashboards for actionable user and content engagement insights.

Applied advanced SQL techniques for data aggregation, joining, and view optimization.
