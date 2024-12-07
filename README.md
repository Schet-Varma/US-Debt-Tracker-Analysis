# 🏛️ US Debt Tracker Project <br>

The US Debt Tracker Project is a comprehensive analysis of US debt data, utilizing advanced Excel techniques to explore trends, identify patterns, and forecast future scenarios. The project delivers key insights into the debt held by the public, intragovernmental holdings, and total public debt outstanding.

## 📂 Project Workflow

<h3>1️⃣ Initial Data Preparation</h3>

Transforming raw data into an analyzable format was the first step. Key preparation processes included:<br>
	•	Transpose Data: Converted columns into rows for better readability and manipulation.<br>
	•	Filter Blank Values: Removed rows with missing data to ensure consistency.<br>
	•	Replace Nulls: Used Find & Replace (Ctrl+H) to remove “null” entries.<br>
	•	Convert Scientific Notation: Formatted numbers from scientific notation to standard n<br>umeric format.<br>
	•	Extract Year-End Dates: Filtered the date column to keep only the last days of each year.<br><br>
 
 <h3>2️⃣ Advanced Data Manipulation Techniques</h3>

Several advanced Excel functions and tools were employed to process and analyze the data:<br><br>
	•	Pivot Tables:<br>
			&nbsp;&nbsp;&nbsp;&nbsp;Used to summarize and analyze large datasets quickly.<br>
			&nbsp;&nbsp;&nbsp;&nbsp;Created yearly summaries for the percentage increase in public debt, intragovernmental holdings, and total debt.<br><br>
			&nbsp;&nbsp;&nbsp;&nbsp;Grouped data by months to calculate average monthly debts.<br>
	•	Advanced Filtering:<br>
			&nbsp;&nbsp;&nbsp;&nbsp;Applied custom filters to isolate key trends, such as year-end totals or specific monthly patterns.<br>
			&nbsp;&nbsp;&nbsp;&nbsp;Extracted records corresponding to significant spikes or anomalies for closer inspection.<br><br>
	•	Conditional Formatting:<br>
			&nbsp;&nbsp;&nbsp;&nbsp;Highlighted spikes in debt increase during specific months or years.<br>
			&nbsp;&nbsp;&nbsp;&nbsp;Color-coded year-over-year trends for easier visualization.<br><br>
	•	Dynamic Ranges: <br>
 			&nbsp;&nbsp;&nbsp;&nbsp;Leveraged named ranges to automate chart updates when data changes.<br><br>

## 📊 Key Analysis & Findings

1. Yearly Debt Percentage Increase<br>

	•	Technique:<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Used Pivot Tables to calculate yearly percentage changes.<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Visualized the trends using a multi-series line chart.<br><br>
	•	Insight:<br>
	&nbsp;&nbsp;&nbsp;&nbsp;From 2012–2019, the average yearly increase in public debt was ~5%.<br>
	&nbsp;&nbsp;&nbsp;&nbsp;A sharp spike in 2020 (~25% increase) was observed, likely due to COVID-19 pandemic policies.<br><br>

2. Monthly Average Total Debts<br>

	•	Technique:
	&nbsp;&nbsp;&nbsp;&nbsp;Used grouped Pivot Tables to calculate monthly averages across all years.<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Represented findings in a bar chart.<br><br>
	•	Insight:
	&nbsp;&nbsp;&nbsp;&nbsp;Highest increases: January, February, November, and December (holiday spending and tax-related activities).<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Lowest increases: April, May, June, and July (typically less fiscal activity).<br><br>

3. Projected Publicly Held Debt<br>

	•	Technique:
	&nbsp;&nbsp;&nbsp;&nbsp;Calculated debt projections based on historical trends using Excel’s Forecast Sheet and linear regression models.<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Visualized growth using a line chart for 2023–2027.<br><br>
	•	Insight:<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Debt rose from $6 trillion to $17 trillion between 2008 and 2019.<br>
	&nbsp;&nbsp;&nbsp;&nbsp;Projected to reach $33 trillion by 2027.<br><br>


## 🛠️ Tools and Techniques Used<br>

  •	Excel Pivot Tables:<br>
  &nbsp;&nbsp;&nbsp;&nbsp;Summarized data by year and month for key metrics like total debt, debt held by the public, and intragovernmental holdings.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;Grouped data dynamically for various levels of aggregation.<br><br>
  •	Filtering:<br>
  &nbsp;&nbsp;&nbsp;&nbsp;pplied custom filters to isolate significant patterns and anomalies.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;Cleaned noisy or irrelevant data to maintain focus on key insights.<br><br>
  •	Find and Replace: Simplified data cleaning by replacing “null” or inconsistent entries with blanks.<br><br>
  •	Conditional Formatting: Highlighted significant spikes in debt or deviations from trends.<br><br>
  •	Forecast Sheet: Leveraged built-in Excel tools to create debt projections.<br><br>
  •	Dynamic Named Ranges: Automated updates to charts and pivot tables as data changed.<br><br>
  •	Chart Creation: Created professional visualizations, including:<br>
  &nbsp;&nbsp;&nbsp;&nbsp;Multi-series line charts for trends.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;Bar charts for monthly and yearly comparisons.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;Forecasting charts for future growth.<br><br>


## 📊 Visual Outputs

1.	Yearly Debt Percentage Increase Chart<br>
2.	Monthly Average Total Debts Chart<br>
3.	Projected Publicly Held Debt Chart<br>

## 🧾 Key Takeaways

This project demonstrates how advanced Excel techniques can be applied to large datasets for meaningful financial analysis. The insights derived here are valuable for understanding past trends, predicting future debt growth, and making informed fiscal policy decisions.
