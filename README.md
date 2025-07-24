## Project Overview

This project involves the analysis and visualization of user session data to understand user behavior and engagement patterns. The primary goal is to track the user journey from the initial search to the final booking, identifying key trends, metrics, and conversion rates. The final output is an interactive dashboard that provides clear, actionable insights from the data spanning from **May 5, 2014, to April 23, 2015**.

## Dataset

The dataset contains anonymized user session data. Key activities tracked include user searches, messages sent, and booking requests.

* **Date Range:** 2014-05-05 to 2015-04-23

## Tools Used

* **Data Transformation:** Power Query
* **Data Visualization:** Power BI
* **Data Source:** CSV file

## Methodology

The project followed a structured process from data cleaning to visualization.

### 1. Data Cleaning and Transformation

Before analysis, the raw dataset required significant cleaning and transformation to ensure accuracy and create useful features:

* **Handling Null Values:** Null values in session-related columns were systematically replaced with the string `Unknown_Session`. This prevents data loss and ensures that incomplete records are still accounted for during analysis.
* **Feature Engineering:** A key descriptive column was split using the delimiter ` - ` (space-hyphen-space). This created new, more granular columns, allowing for a deeper and more precise analysis of session attributes.

### 2. Data Visualization & Dashboarding

An interactive dashboard was created to present the findings. The choice of visualizations was driven by the goal of making the data intuitive and easy to explore.

## Key Visualizations & Insights

The dashboard is composed of several key components:

### 📊 KPI Cards
* **Purpose:** To display the most important, high-level numbers at a glance.
* **Metrics:** Total Searches, Total Messages, Total Booking Requests.
* **Insight:** Provides an immediate summary of the overall activity volume on the platform.

### 📈 Line Chart
* **Purpose:** To track user activity over time.
* **Analysis:** Shows the trends of searches, messages, and booking requests on a daily, weekly, or monthly basis.
* **Insight:** Helps identify seasonality, peak activity periods, and the impact of any external events on user engagement.

### 🔽 Funnel Chart
* **Purpose:** To visualize the user's journey and measure conversion rates between key stages.
* **Analysis:** Maps the flow of users from an initial search, to sending a message, to making a booking request.
* **Insight:** This is the core of the conversion analysis. It clearly highlights the percentage of users who drop off at each stage, allowing for targeted strategies to improve the user experience and increase bookings.

### 🖱️ Slicer
* **Purpose:** To make the report interactive and user-friendly.
* **Functionality:** Allows users of the dashboard to filter the entire report by a specific date range or category.
* **Insight:** Empowers stakeholders to self-serve insights and explore data relevant to their specific questions without needing a new report.
