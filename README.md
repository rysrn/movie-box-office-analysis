# Movie-box-office-analysis

## Korean Movie Box Office Analysis (2010– April 2025)

A comprehensive data analysis project examining the trends, regional spending behavior, age-rating impacts, and historical evolution of the South Korean cinema industry using Microsoft Excel.

## 📊 Project Overview
This project processes historical Korean box office data to uncover insights into viewer habits, economic trends, and structural shifts in the industry—specifically tracking the sector's growth up to its 2019 peak and its subsequent post-pandemic recovery phase.

## 📁 Dataset & Data Cleaning Workflow
The original dataset was provided as a raw comma-delimited (`.csv`) file and converted to an Excel workbook (`.xlsx`) to prevent data loss and preserve advanced formatting.

The following data cleaning and preparation steps were performed:
*   **Column Optimization:** Adjusted all column widths to ensure data and header text were fully visible (resolving `###` display errors).
*   **Header Standardization:** Automated header formatting using the `=PROPER()` function to capitalize header names uniformly, replacing the original raw headers using **Paste Special > Values Only**.
*   **Currency Standardization:** Converted raw numerical financial columns from *General* format into formatted Korean Won (`₩`) currency fields.

---

## 📈 Key Insights & Analysis

### Q1: Genre Popularity Over Time
*   **Methodology:** Built a Pivot Table tracking film counts per genre over time and visualized the trends using a Line Graph with Markers.
*   **Finding:** Clear visual indicators reveal which genres dominated Korean cinema year-over-year, showcasing changing consumer entertainment tastes.

### Q2: Audience Turnout vs. Revenue by Region (Seoul vs. Nationwide)
*   **Volume Comparison:** Audiences outside of Seoul spent a combined **₩14.8 trillion**, compared to **₩5.8 trillion** within Seoul. This macro difference is expected given the population distribution outside a single metropolitan center.
*   **Per-Capita Spending:** On a per-person basis, Seoul moviegoers spent an average of **₩8,622 per ticket**—roughly **5.8% more** than the **₩8,147** nationwide average.
*   **Takeaway:** This indicates a localized premium in the capital city, likely driven by a higher density of premium-format screens (IMAX, 4DX) or higher ticket pricing tiers.

### Q3: Age Ratings and Box Office Impact
*   **Per-Ticket Consistency:** Age ratings have a negligible impact on individual moviegoer spending. Audiences spend consistently between **₩8,072 and ₩8,509 per person** regardless of the film's rating (a minimal 5% spread).
*   **Revenue Share Dominance:** Total market share is highly uneven. **15+ rated films dominate the market with 40.3% of total revenue**, closely followed by **12+ films at 37.3%**. "All Ages" films capture 13.5%, while "18+" restricted films account for only 8.9%.
*   **Takeaway:** The commercial success of an age rating category relies entirely on volume and audience accessibility (reach), not on how much individual viewers are willing to spend per ticket.

### Q4: Industry Evolution (From *Myeongryang* to *Parasite* and Beyond)
*   **The Golden Era (2014–2019):** Following the release of *Myeongryang* (2014) up to *Parasite* (2019), the Korean film industry experienced steady, robust expansion. Total screens, film output, and ticket sales peaked in 2019 with **226 million admissions across 1,943 films**.
*   **The Pandemic Shock (2020):** The COVID-19 pandemic caused a catastrophic **77% collapse in audience attendance** in 2020.
*   **The Recovery Phase (2021–2025):** The recovery process has been structurally slow. By 2024, audience volume plateaued at roughly half of pre-pandemic levels. The industry is outputting significantly fewer films than its 2019 peak, indicating a permanently downsized market structure.

---

## 🛠️ Tools Used
*   **Microsoft Excel:** Data Cleansing, Formulas (`PROPER`, text adjustments), Pivot Tables, and Data Visualization (Line and Column Charts).
