# AI Job Displacement & Market Impact Analysis (2026)

## Project Overview
A comprehensive data analysis and visualization of the 2026 AI-driven job cut tracker. This project explores the macroeconomic impact of artificial intelligence on the workforce, analyzing how corporate AI investments correlate with layoffs, stock market reactions, and the elimination of specific job roles.

## The Business Problem
As AI capabilities accelerate, workforce development agencies and policymakers need to understand the exact nature of job displacement. Are companies actually replacing workers with AI, or using AI as a scapegoat for pandemic over-hiring? Which sectors are most vulnerable, and how does the market react when a company announces an "AI-driven" layoff?

## Technical Stack
*   **Data Analysis:** Python (Pandas, NumPy)
*   **Machine Learning:** Scikit-Learn
*   **Visualization:** Power BI / Tableau
*   **Dataset:** 2026 Global Tech & Enterprise Layoff Tracker

## Key Analyses & Insights

### 1. The "AI Scapegoat" Paradox
*   **The Question:** Are companies that cite AI as a reason for layoffs actually increasing their AI spending?
*   **The Finding:** Discovered a strong correlation between `simultaneous_ai_investment_bn` and `jobs_cut`. (e.g., Meta cutting 16,000 jobs while investing heavily in AI infrastructure). 
*   **The Insight:** Companies are reallocating human capital budgets directly into AI capital expenditures.

### 2. Stock Market Reaction vs. AI Mentions
*   **The Question:** Does Wall Street reward companies that explicitly cite AI as a reason for layoffs?
*   **The Finding:** Analyzed `stock_change_day_pct` against the `ai_cited` boolean column. [Insert your finding here, e.g., "Companies that cited AI saw an average stock bump of X%, compared to Y% for those that cited 'restructuring'."]

### 3. Predictive Modeling: The Next Wave of Layoffs
*   **The Model:** Built a Machine Learning Classification model (Random Forest) to predict the `layoff_size_category` (Small/Medium/Large/Mega) based on company revenue, historical layoffs (2024/2025), and AI investment.
*   **The Result:** The model identifies which sectors are most mathematically vulnerable to AI-driven cuts in Q3 and Q4 of 2026.

### 4. Workforce Role Mapping (NLP)
*   Analyzed the `roles_most_affected` and `replacement_roles` columns to identify the specific transition. 
*   [Insert finding, e.g., "Customer Success and Data Entry roles are being replaced by AI Operations and Prompt Engineering roles."]

## Interactive Dashboard (Power BI)
*   **Global Heatmap:** Visualizing layoffs by Country and Region.
*   **The Sector Breakdown:** A drill-down of which industries (Enterprise Software, Social Media, Cybersecurity) are bleeding the most jobs.
*   **The Time Series:** Tracking layoff frequency month-by-month from January to March 2026.

## Status
🚧 **Work in Progress:** The Jupyter Notebook for the ML model and the Power BI dashboard files will be uploaded shortly.
