# Wine-Tasting
# 🍷 Beyond the Bottle

## 1. Project Title / Headline

# Beyond the Bottle — Global Wine Analytics Dashboard

An interactive **Power BI dashboard** that analyzes global wine reviews to uncover trends in wine pricing, ratings, countries, regions, wineries, and varieties.

---

## 2. Short Description / Purpose

**Beyond the Bottle** is an interactive Power BI dashboard built to explore global wine trends using over **120,000 wine reviews**.

The dashboard helps users understand how **wine prices, ratings, countries, provinces, wineries, and varieties** vary across the global wine market and provides data-driven insights into premium wine markets and regional preferences.

---

## 3. Tech Stack

* **Power BI** — Dashboard development and data visualization
* **Power Query** — Data cleaning, transformation, and preparation
* **DAX** — Measures, KPIs, calculations, and analytical logic
* **Microsoft Excel** — Initial data exploration and data preparation
* **GitHub** — Project documentation and portfolio presentation

---

## 4. Data Source

The dataset is based on the **Wine Enthusiast wine reviews dataset** provided through Maven Analytics.

The original dataset contains information about thousands of wines reviewed by Wine Enthusiast, including attributes such as:

* Wine country
* Province / region
* Winery
* Wine variety
* Wine title
* Reviewer / taster
* Wine rating / points
* Wine price
* Designation
* Description

### Data Preparation

The dataset was cleaned and transformed using **Power Query** before being used in Power BI.

Key preparation steps included:

* Handling missing values
* Removing incomplete records where required
* Cleaning categorical fields
* Standardizing country and regional information
* Preparing price and rating fields for analysis
* Creating analytical categories such as **Coastal vs Landlocked countries**
* Creating calculated measures using **DAX**

After data preparation, the dashboard contains approximately **120,913 wine reviews across 42 countries, 15,820 wineries, 692 wine varieties, and 20 wine tasters**.

---

# 5. Features and Highlights

## A. Business Problem

The global wine market contains a large amount of review and pricing data, making it difficult to identify meaningful trends manually.

The key business questions addressed by this dashboard are:

* Which countries have the highest average wine prices?
* Does a higher wine price generally correspond to a higher rating?
* Which countries and regions have the strongest wine representation?
* How do wine prices and ratings vary across provinces?
* Which wine varieties are popular in different regions?
* Which regions are associated with premium or affordable wines?
* How does reviewer activity vary geographically?

---

## B. Goal of the Dashboard

The primary goal of **Beyond the Bottle** is to transform raw wine review data into an interactive analytical tool that helps users:

1. Understand global wine pricing and rating patterns.
2. Compare wine markets across countries and regions.
3. Identify premium wine-producing markets.
4. Explore regional differences in wine varieties.
5. Analyze reviewer coverage and activity.
6. Discover relationships between **wine price and quality ratings**.

---

## C. Walkthrough of Key Visuals

### 📊 Page 1 — Executive Overview

The Executive Overview provides a high-level summary of the global wine dataset.

### Key KPIs

The dashboard highlights:

* **120,913** Total Wine Reviews
* **42** Countries Covered
* **15,820** Wineries Reviewed
* **692** Wine Varieties
* **20** Wine Tasters

### Top 10 Countries by Average Wine Price

A horizontal bar chart compares the average wine price across the top 10 countries.

The analysis shows that:

* **Germany, France, and Italy** have the highest average wine prices among the countries displayed.
* Premium pricing is concentrated across several established wine-producing markets.
* The chart also categorizes countries based on **Coastal vs Landlocked** geography.

### Average Wine Rating by Price Band

The line chart analyzes average wine ratings across different price ranges, from wines priced below **$20** to wines priced above **$1,000**.

Key observation:

> Wine ratings generally increase as price increases, but the improvement becomes relatively marginal at higher price points.

This indicates that spending significantly more on wine does not necessarily result in a proportionally higher rating.

---

## 🌍 Page 2 — Geographical Insights

The Geographical Insights page allows users to explore wine trends at the **country and province level**.

### Country & Province Slicers

Interactive slicers allow users to select:

* Country
* Province

The province selection dynamically responds to the selected country, allowing users to explore regional-level wine trends.

### Average Price vs Average Rating

A combined chart compares:

* Average Wine Price
* Average Wine Rating

across provinces.

This helps identify regions that produce relatively **high-rated wines** and understand how pricing differs between regions.

### Number of Reviewers per Province

The dashboard provides a geographical view of reviewer activity, helping identify differences in reviewer coverage across provinces.

### Variety Analysis

The variety-level table provides detailed information including:

* Wine variety
* Number of tasters
* Number of wine titles
* Number of designations
* Average value score
* Rating
* Price

This allows users to drill into specific wine varieties and compare their pricing and ratings.

---

## D. Business Impact and Insights

The dashboard provides several key business insights:

### 🍷 Premium Wine Markets

**Germany, France, and Italy** show some of the highest average wine prices in the analyzed dataset, indicating strong premium-market positioning.

### 📈 Price vs Rating

Wine ratings generally increase with price, but the increase becomes **less significant at higher price levels**.

This suggests that premium pricing does not always translate into proportionally higher perceived quality.

### 🌎 Regional Differences

Wine pricing and ratings vary considerably between provinces, demonstrating the importance of **regional characteristics and wine-making traditions**.

### 🍇 Variety Preferences

Popular wine varieties differ by location, highlighting the influence of **regional wine-making practices and consumer preferences**.

### 👥 Reviewer Distribution

Reviewer activity is not evenly distributed across regions, indicating differences in geographical representation within the dataset.

---

# 6. Screenshot

## Executive Overview

![Beyond the Bottle - Executive Overview](https://github.com/priyanshityagi21/Wine-Tasting/blob/main/Executive%20Overview.png)

## Geographical Insights

![Beyond the Bottle - Geographical Insights](./screenshots/Geographical%20Insights.png)

---


**Beyond the Bottle** transforms a large wine-review dataset into an interactive business intelligence solution that makes global wine trends easier to understand.

The project demonstrates how **data cleaning, DAX, visualization, and storytelling** can be combined to turn raw data into act
