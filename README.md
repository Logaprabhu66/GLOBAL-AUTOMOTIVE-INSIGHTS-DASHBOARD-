**Global Automotive Insights Dashboard – Power BI**

---

### 2. Project Overview

The Global Automotive Insights Dashboard is an interactive Business Intelligence solution developed using Power BI to analyze and visualize automotive industry data. The dashboard provides insights into vehicle sales performance, pricing, battery specifications, charging capabilities, safety ratings, and geographical market distribution.

The primary objective of this project is to help stakeholders, analysts, and decision-makers monitor key performance indicators (KPIs) and identify trends within the global automotive market.

---

### 3. Objectives

* Analyze global automotive sales performance.
* Monitor total vehicle revenue and sales units.
* Compare vehicle variants and model performance.
* Evaluate battery capacity and charging speed metrics.
* Assess vehicle safety ratings across different models.
* Visualize country-wise sales distribution.
* Enable interactive exploration through filters and slicers.

---

### 4. Tools & Technologies Used

| Tool        | Purpose                        |
| ----------- | ------------------------------ |
| Power BI    | Dashboard Development          |
| Power Query | Data Cleaning & Transformation |
| DAX         | KPI Calculations & Measures    |
| Excel/CSV   | Data Source                    |
| Bing Maps   | Geographical Visualization     |

---

### 5. Dataset Description

The dataset contains information related to:

* Vehicle Models
* Vehicle Variants
* Manufacturer Details
* Country of Origin
* Annual Sales Units
* Vehicle Price (USD)
* Battery Capacity (kWh)
* Charging Speed (kW)
* Safety Ratings
* Drive Type (FWD, RWD, AWD)

---

### 6. Dashboard KPIs

#### Total Price in USD

* **157.75 Million USD**
* Represents the total market value of vehicles included in the dataset.

#### Annual Sales by Unit

* **259 Million Units**
* Indicates total vehicle sales volume.

#### Safety Rating

* **9K**
* Aggregated safety rating score across all vehicle segments.

---

### 7. Dashboard Visualizations

#### A. Model & Variant Filter

* Allows users to select specific vehicle models and variants.
* Enables detailed analysis for individual vehicles.

#### B. Vehicle Image Visualization

* Displays vehicle images dynamically for enhanced user experience.

#### C. Country Origin and Annual Sales Map

* Interactive geographical map showing sales distribution across regions.
* Highlights major automotive markets.

#### D. Annual Sales Units by Variant

* Line chart displaying sales trends for:

  * Base
  * Long Range
  * Standard
  * Premium
  * Performance

**Insights:**

* Long Range variants show higher sales in several models.
* Premium and Performance variants contribute significantly to revenue.

#### E. Battery Capacity & Charging Speed

* Donut chart comparing battery capacity and charging speed distribution.
* Categorized by:

  * AWD
  * FWD
  * RWD

**Insights:**

* AWD vehicles contribute the largest battery capacity share.
* Charging performance varies significantly among drive types.

#### F. Safety Rating by Model

* Stacked bar chart comparing safety ratings among vehicle models.

**Insights:**

* Several premium models demonstrate superior safety performance.
* Useful for identifying safety leaders in the market.

---

### 8. Data Cleaning & Transformation Process

Performed using Power Query:

* Removed duplicate records.
* Handled missing values.
* Standardized vehicle model names.
* Converted data types.
* Created calculated columns.
* Optimized dataset structure for reporting.

---

### 9. DAX Measures Created

Examples:

```DAX
Total Sales = SUM(Sales[Annual_Sales])

Total Revenue = SUM(Sales[Price_USD])

Average Safety Rating = AVERAGE(Sales[Safety_Rating])

Total Battery Capacity = SUM(Sales[Battery_Capacity_kWh])
```

---

### 10. Key Business Insights

1. Total automotive market value exceeds **$157 Million**.
2. Annual sales volume reaches **259 Million Units**.
3. Long Range and Premium variants drive significant sales.
4. AWD vehicles dominate battery capacity distribution.
5. Safety ratings vary considerably between vehicle models.
6. North America and Asia contribute heavily to automotive sales.

---

### 11. Business Benefits

* Supports strategic decision-making.
* Identifies top-performing vehicle models.
* Tracks market trends and customer preferences.
* Evaluates vehicle safety standards.
* Assists in sales forecasting and market expansion planning.

---

### 12. Conclusion

The Global Automotive Insights Dashboard successfully transforms raw automotive data into meaningful business insights. By integrating sales, pricing, battery performance, safety ratings, and geographical analysis into a single interactive platform, the dashboard enables stakeholders to make data-driven decisions efficiently. The project demonstrates strong skills in Power BI, DAX, data modeling, visualization design, and business intelligence reporting.

**Skills Demonstrated:** Power BI • DAX • Power Query • Data Modeling • Data Visualization • Business Intelligence • Dashboard Design • Data Analysis.
