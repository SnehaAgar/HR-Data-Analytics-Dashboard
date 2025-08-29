# HR Data Analytics Dashboard

A dynamic, interactive data visualization tool to explore detailed HR metrics—employee demographics, department-level analytics, attrition trends, job satisfaction, and workforce KPIs—to support strategic decision-making for human resources teams.

---

## Table of Contents

* [Purpose](#purpose)
* [Tech Stack](#tech-stack)
* [Dataset](#dataset)
* [Features](#features)
* [Key Visuals](#key-visuals)
* [Business Impact & Insights](#business-impact--insights)
* [Getting Started](#getting-started)
* [How to Use the Dashboard](#how-to-use-the-dashboard)
* [File Formats](#file-formats)
* [Screenshot](#screenshot)

---

## Purpose

The **HR Analytics Dashboard** is a visually engaging **Power BI** report that provides HR professionals and stakeholders with **actionable insights** on workforce composition, attrition rates, employee satisfaction, and department performance. It helps organizations **optimize talent management**, **reduce attrition**, and **improve employee engagement** by highlighting critical trends and patterns in HR data.

---

## Tech Stack

* **Power BI Desktop** — main platform for data modeling and interactive dashboard creation
* **Power Query** — data transformation and preprocessing layer for reshaping and cleaning the source data
* **DAX (Data Analysis Expressions)** — calculated metrics, dynamic visuals, and custom logic in reporting
* **Data Modeling** — relationships established among **HR**, **employee**, and **job satisfaction** tables for cross-filtering and aggregation
* **File Formats** — `.pbix` for development; `.png`/`.jpg` for dashboard previews

---

## Dataset

The dashboard leverages organizational HR datasets containing:

* **Employee information:** age, gender, education, department, job role
* **Attrition history**
* **Satisfaction ratings**

Data is collected at the **department** and **employee** level, enabling **trend** and **comparative** analysis across HR fields.

---

## Features

### Business Problem

Organizations struggle to quickly understand workforce health, identify causes of high attrition, and address job satisfaction issues.

### Goal

Provide a **consolidated**, **easy-to-navigate** dashboard for exploring **HR KPIs**, **at‑risk groups**, and **department performance** to inform retention strategies and workforce planning.

---

## Key Visuals

* **🔢 KPIs Section** — high-level workforce metrics:

  * **Overall Employees**
  * **Attrition**
  * **Attrition Rate**
  * **Active Employees**
  * **Average Age**

* **🏢 Department-wise Attrition** — pie chart to pinpoint departments most affected by attrition (e.g., **R\&D**, **Sales**, **HR**)

* **👥 Age & Gender Distribution** — visuals by **gender** and **age group** to reveal diversity and generational trends

* **🎓 Education Field-wise Attrition** — bar chart highlighting attrition rates by educational background (**Medical**, **Life Sciences**, **Technical**, etc.)

* **📊 Attrition Rate by Gender & Age** — ring/donut charts showing attrition split by gender across age bands to surface high-risk segments

* **⭐ Job Satisfaction Rating** — matrix table summarizing employee satisfaction levels by job role to aid targeted engagement initiatives

---

## Business Impact & Insights

* **🎯 Talent Retention** — identify departments and education fields with **high attrition** to drive targeted retention programs
* **📋 Workforce Planning** — breakdown by **age**, **gender**, and **role** supports diversity and succession planning
* **💪 Employee Engagement** — satisfaction analysis helps pinpoint and address factors influencing morale and performance

---

## Getting Started

1. **Clone or download** this repository.
2. Open the `.pbix` file in **Power BI Desktop** (latest version recommended).
3. If needed, update data source paths in **Power Query** and click **Refresh**.
4. Interact with slicers and visuals to explore insights.

> ℹ️ For GitHub Markdown formatting, see the official guide: *Basic writing and formatting syntax*.

---

## How to Use the Dashboard

* Use **slicers** (e.g., Department, Education, Gender, Age Band) to filter the entire report.
* Hover for **tooltips** to view detailed metrics.
* Click any visual element to **cross-filter** related charts and tables.
* Review **KPI cards** for a health check of overall workforce metrics.

---

## File Formats

* **Development:** `.pbix`
* **Previews/Exports:** `.png`, `.jpg`

---

## Screenshot

![HR Analytics Dashboard Preview](https://github.com/SnehaAgar/HR-Data-Analytics-Dashboard/blob/main/HR_ANALYTICS.png)

---

> **Note:** Data used in this dashboard represents typical HR attributes and structures for analytics. Replace or connect to your organization’s secure datasets as required.
