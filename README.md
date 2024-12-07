# 🏛️ US Debt Tracker Project <br>

The US Debt Tracker Project is a comprehensive analysis of US debt data, utilizing advanced Excel techniques to explore trends, identify patterns, and forecast future scenarios. The project delivers key insights into the debt held by the public, intragovernmental holdings, and total public debt outstanding.

## 📂 Project Workflow

<h3>1️⃣ Initial Data Preparation</h3>

Transforming raw data into an analyzable format was the first step. Key preparation processes included:
	•	Transpose Data: Converted columns into rows for better readability and manipulation.
	•	Filter Blank Values: Removed rows with missing data to ensure consistency.
	•	Replace Nulls: Used Find & Replace (Ctrl+H) to remove “null” entries.
	•	Convert Scientific Notation: Formatted numbers from scientific notation to standard numeric format.
	•	Extract Year-End Dates: Filtered the date column to keep only the last days of each year.
 
 <h3>2️⃣ Advanced Data Manipulation Techniques</h3>

Several advanced Excel functions and tools were employed to process and analyze the data:
	•	Pivot Tables:
	•	Used to summarize and analyze large datasets quickly.
	•	Created yearly summaries for the percentage increase in public debt, intragovernmental holdings, and total debt.
	•	Grouped data by months to calculate average monthly debts.
	•	Advanced Filtering:
	•	Applied custom filters to isolate key trends, such as year-end totals or specific monthly patterns.
	•	Extracted records corresponding to significant spikes or anomalies for closer inspection.
	•	Conditional Formatting:
	•	Highlighted spikes in debt increase during specific months or years.
	•	Color-coded year-over-year trends for easier visualization.
	•	Dynamic Ranges: Leveraged named ranges to automate chart updates when data changes.

## 📊 Key Analysis & Findings

1. Yearly Debt Percentage Increase

	•	Technique:
	•	Used Pivot Tables to calculate yearly percentage changes.
	•	Visualized the trends using a multi-series line chart.
	•	Insight:
	•	From 2012–2019, the average yearly increase in public debt was ~5%.
	•	A sharp spike in 2020 (~25% increase) was observed, likely due to COVID-19 pandemic policies.

2. Monthly Average Total Debts

	•	Technique:
	•	Used grouped Pivot Tables to calculate monthly averages across all years.
	•	Represented findings in a bar chart.
	•	Insight:
	•	Highest increases: January, February, November, and December (holiday spending and tax-related activities).
	•	Lowest increases: April, May, June, and July (typically less fiscal activity).

3. Projected Publicly Held Debt

	•	Technique:
	•	Calculated debt projections based on historical trends using Excel’s Forecast Sheet and linear regression models.
	•	Visualized growth using a line chart for 2023–2027.
	•	Insight:
	•	Debt rose from $6 trillion to $17 trillion between 2008 and 2019.
	•	Projected to reach $33 trillion by 2027.


## 🛠️ Tools and Techniques Used

  •	Excel Pivot Tables:
  •	Summarized data by year and month for key metrics like total debt, debt held by the public, and intragovernmental holdings.
  •	Grouped data dynamically for various levels of aggregation.
  •	Filtering:
  •	Applied custom filters to isolate significant patterns and anomalies.
  •	Cleaned noisy or irrelevant data to maintain focus on key insights.
  •	Find and Replace: Simplified data cleaning by replacing “null” or inconsistent entries with blanks.
  •	Conditional Formatting: Highlighted significant spikes in debt or deviations from trends.
  •	Forecast Sheet: Leveraged built-in Excel tools to create debt projections.
  •	Dynamic Named Ranges: Automated updates to charts and pivot tables as data changed.
  •	Chart Creation: Created professional visualizations, including:
  •	Multi-series line charts for trends.
  •	Bar charts for monthly and yearly comparisons.
  •	Forecasting charts for future growth.


## 📊 Visual Outputs

  1.	Yearly Debt Percentage Increase Chart
  2.	Monthly Average Total Debts Chart
	3.	Projected Publicly Held Debt Chart

## 🧾 Key Takeaways

This project demonstrates how advanced Excel techniques can be applied to large datasets for meaningful financial analysis. The insights derived here are valuable for understanding past trends, predicting future debt growth, and making informed fiscal policy decisions.
