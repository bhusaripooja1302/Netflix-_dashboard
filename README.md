# Netflix Users Dashboard 📊

## 📌 Project Overview

The **Netflix Users Dashboard** is an interactive Power BI dashboard created to analyze user behavior, subscription types, watch time, favorite genres, age groups, countries, and login activity.

The dashboard provides a clear overview of Netflix user data and helps identify patterns in user engagement and subscriptions.

---

## 🎯 Project Objective

The main objective of this project is to:

- Analyze Netflix users and their subscription types
- Understand user watch-time behavior
- Analyze users by age group and country
- Identify the most popular genres
- Compare watch hours across subscription types
- Analyze user activity based on last login
- Create an interactive and visually appealing Power BI dashboard

---

## 🛠️ Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **CSV Dataset**
- **Data Visualization**

---

## 📂 Dataset

The dataset contains **25,000 Netflix users**.

### Dataset Columns

| Column | Description |
|---|---|
| User_ID | Unique ID of the user |
| Name | User name |
| Age | Age of the user |
| Country | User's country |
| Subscription_Type | Basic, Standard, or Premium |
| Watch_Time_Hours | Total watch time in hours |
| Favorite_Genre | User's favorite genre |
| Last_Login | User's last login date |

---

## 📊 Dashboard KPIs

The dashboard includes the following key performance indicators:

- **Total Users:** 25K
- **Total Watch Hours:** 12.51M
- **Average Watch Hours/User:** 500.47
- **Premium Users:** 8K
- **Total Genres:** 7
- **Total Countries:** 10

---

## 📈 Dashboard Visualizations

### Page 1 – User & Subscription Analysis

The first dashboard page contains:

- Users by Subscription Type
- Users by Age Group
- Watch Hours by Subscription Type
- Watch Hours by Last Login
- Users by Favorite Genre
- Interactive filters for:
  - Subscription Type
  - Favorite Genre
  - Age
  - Country
  - Last Login

### Page 2 – User Demographic Analysis

The second dashboard page contains:

- Users by Country
- Watch Hours by Favorite Genre
- Age by Country and Favorite Genre
- Age by Year
- Interactive filters for user analysis

---

## 🎛️ Interactive Features

Users can filter the dashboard using:

- Subscription Type
- Favorite Genre
- Age
- Country
- Last Login

The **Reset** button can be used to clear the selected filters.

---

## 🔍 Key Insights

Some of the insights available from the dashboard include:

- The dataset contains **25K users**.
- Premium, Standard, and Basic subscriptions have a relatively balanced user distribution.
- Users have generated more than **12 million watch hours**.
- There are **7 different favorite genres** in the dataset.
- The dashboard allows comparison of user activity across **10 countries**.
- Genre-level analysis helps identify the most preferred content categories.
- Login-date analysis provides an overview of user engagement over time.

---


## 📁 Project Files

```text
Netflix-_dashboard/
│
├── netflix_users(1).csv
├── Netflix Dashboard.pbix
├── netflix_dashboard ss1.PNG
├── netfix_dashboard ss2.PNG
└── README.md
