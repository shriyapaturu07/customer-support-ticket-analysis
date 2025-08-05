# Customer Support Ticket Analysis 📊

This project analyzes customer support ticket data using PostgreSQL and visualizes key insights using Tableau. It demonstrates how to derive actionable insights such as resolution efficiency, customer satisfaction, and service bottlenecks.

## 🔍 Project Overview

**Goal:**  
Analyze customer support performance using SQL, with a focus on:

- Average resolution time
- Ticket volume by priority
- Customer satisfaction scores
- Identification of overdue tickets (past 48 hours)

**Tools Used:**
- PostgreSQL
- Tableau (for visualization)
- pgAdmin (for SQL querying)

## 🗂️ Dataset

The dataset contains support ticket records with fields like:

- Ticket ID
- Customer demographics
- Ticket type and status
- Response and resolution timestamps
- Customer satisfaction rating

The cleaned version of the dataset was imported into a PostgreSQL table named `support_tickets`.

## 🧱 SQL Views Created

1. `ticket_count_by_priority` – Total tickets grouped by priority level  
2. `satisfaction_by_priority` – Average customer satisfaction by ticket priority  
3. `avg_resolution_time` – Overall average resolution time in hours  
4. `overdue_tickets` – Flags tickets that exceeded the 48-hour SLA  
5. `ticket_preview` – Sample of the raw dataset (first 10 records)

> All view definitions are saved in [customer_support_views.sql](customer_support_views.sql)

## 📈 Visualizations

Tableau was used to create dashboards for:
- Resolution time trends
- Satisfaction distribution
- Priority-driven ticket flow

(Include screenshots or links to Tableau Public if applicable)

## 📁 How to Use

1. Import the dataset into PostgreSQL
2. Run the SQL script to create all views:
   ```sql
   \i customer_support_views.sql
   ```
3. Connect Tableau to PostgreSQL to start visualizing the views

---

## ✍️ Author

**Shriya Paturu**  
B.S. in Statistics, Concentration in Information Systems  
[LinkedIn](https://www.linkedin.com/) | [Medium](https://medium.com/@shriya_27038)

