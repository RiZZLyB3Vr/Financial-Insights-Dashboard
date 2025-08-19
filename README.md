# My Financial Insights Dashboard 

Hey there! Thanks for checking out my Power BI project. I built this to transform a raw financial dataset into a powerful, interactive dashboard. This wasn't just about making charts; it was about demonstrating the entire data analysis journey, from handling messy data to designing a tool that provides real, actionable insights.

The final result is a clean, dynamic dashboard that tells the story of income, expenses, and savings at a glance.

## Project in Action

!(Financial_Insights_Dashboard_img.jpg)

---

## What Can You Do with This Dashboard?

-   **Get a Financial Snapshot:** Quickly view key metrics like total income, total expenses, and net income with easy-to-read cards.
-   **Find Out Where Your Money Goes:** Instantly see the breakdown of spending across different categories with a clear treemap and matrix.
-   **Track Your Savings Goals:** Use a gauge visual to track your progress toward your desired savings target.
-   **Explore Deeper Trends:** Use the bar charts and donut charts to discover patterns, like how income relates to different occupations and city tiers.

---

## My Process: From Data to Dashboard

### 1. Data Preparation in Power Query

The project began with a raw CSV file. My first step was to prepare the data in **Power Query**. I had to handle inconsistencies and create a new column, `Total_Expenses`, by consolidating all the individual expense columns. This foundational step was crucial for all my later analysis.

### 2. Building the Logic with DAX

With the data clean, I moved on to **DAX** (Data Analysis Expressions). This is the formula language I used to build the "brain" of the dashboard. I created several key measures:

-   `Net Income`: This measure subtracts total expenses from total income, giving a clear view of savings or loss.
-   `Savings Variance`: I created this to compare my net income against the `Desired_Savings` column, showing how well I was performing against my financial goals.

### 3. Telling the Story with Visuals

Finally, I focused on turning the data into a compelling story using a variety of visuals. Each visual was chosen for a specific purpose:

-   **Cards** to highlight critical KPIs.
-   A **Matrix** to provide a detailed, side-by-side comparison of expenses.
-   A **Treemap** to visually represent a proportional breakdown of spending.
-   A **Bar Chart** for comparing totals across occupations.
-   A **Donut Chart** to show the distribution of income by city tier.
-   A **Gauge** visual to track progress toward a specific financial goal.

This process allowed me to connect the technical side of data with the practical, human side of financial analysis. I hope you enjoy exploring it!

---

## Technical Skills Demonstrated

-   **Data Transformation (Power Query):** Cleaning, shaping, and creating new columns from raw data.
-   **DAX Measures:** Writing custom measures to create new metrics and advanced business logic.
-   **Data Visualization:** Selecting and designing the right visuals to communicate a clear story.
-   **Dashboard Design:** Creating a polished and user-friendly report with a cohesive layout.

---
