# ISMSR
Impact of Social Media on Suicide Rates (2010–2019)
Objective of the Project:
This analysis investigates the possible relationship between social media usage (Facebook and Twitter) and suicide rates over a 10-year period (2010–2019). The aim is to explore whether an increase in user count correlates with any notable trends in suicide rates and to uncover gender-based patterns.
Problem Being Addressed:
Mental health issues and suicide rates are global concerns, and social media has been both credited and criticized for its influence. This analysis seeks to understand trends over time and by gender, alongside the growth of social platforms.
Key Datasets and Methodologies:
The data includes suicide rates by year and gender, Facebook and Twitter user counts, and social media usage segmentation. The analysis was conducted in Power BI using KPI cards, line and bar charts, pie charts, and stacked visuals.

3. Story of Data
Data Source:
The dataset appears to be a structured collection of global or national mental health records and social media statistics, likely obtained from public health records and digital platform reports.
Data Collection Process:
Social media metrics were tracked annually, segmented by platform and user count. Suicide rate data was disaggregated by gender and year, ensuring temporal alignment.
Data Structure:
•	Rows: Yearly records (2010–2019)
•	Columns: Suicide rate (total and by gender), Facebook users, Twitter users, gender classification
Important Features and Their Significance:
•	Suicide Rate: Core dependent metric to measure mental health outcomes
•	User Count: Represents exposure or engagement with platforms
•	Gender: Allows demographic comparison
Data Limitations or Biases:
•	Does not capture causation—only correlation
•	No regional breakdown or age group segmentation
•	Social media engagement quality (e.g., time spent, content type) is not considered

4. Data Splitting and Preprocessing
Data Cleaning:
Numeric values were formatted in thousands for easy visualization (e.g., 2.82K).
Handling Missing Values:
All values were available for the 10-year range. No imputation was needed.
Transformations:
Aggregations were used to calculate:
•	Average user counts for Facebook and Twitter
•	Sum and average of suicide rates
•	Suicide rate by gender and platform exposure
Data Splitting:
•	Dependent Variable: Suicide Rate
•	Independent Variables: Facebook users, Twitter users, Gender, Year
Stakeholders:
•	Public health agencies
•	Mental health NGOs and researchers
•	Social media policy teams
•	Educational institutions
Value to the Industry:
Provides data-driven insight into how online environments may influence societal wellbeing trends and mental health discussions.

5. Pre-Analysis
Initial Observations:
•	Suicide rate decreased slightly over time (from 300 in 2010 to 261 in 2019).
•	Facebook user count increased steadily from 300K to 1.23M.
•	Twitter user count showed similar upward momentum from 300 to 1.88K (in thousands).
Key Trend:
There’s a divergence between rising social media usage and declining suicide rate, challenging the popular assumption of a direct negative correlation.

6. In-Analysis
Suicide Rate Trends (Line Chart):
The total suicide rate declined year by year, suggesting potential improvement in mental health services or awareness campaigns.
Facebook User Growth (Bar Chart):
Growth was consistent from 2010 to 2019, reaching over 1.23M users by 2019.
Twitter User Growth (Bar Chart):
More rapid user adoption, peaking at 1.88K by 2019.
Suicide Rate by Gender (Pie Chart):
•	Male: 946.24
•	Female: 926.38
•	BTSX (Non-binary): 942.50
Minimal variation suggests gender-neutral mental health impact in aggregate.
Platform User Count by Gender (Bar Chart):
•	Equal Twitter user distribution across all genders (4,628 each), indicating demographic equality in platform use.
Combined Suicide & Platform Analysis by Gender (Bar Chart):
Each gender group had a consistent Facebook user count (2,554) and closely matched suicide rates (943–946 range), reinforcing non-significant gender gaps.

7. Post-Analysis and Insights
Key Findings:
•	Steady increase in social media usage did not correspond with an increase in suicide rate.
•	Gender differences in suicide rates were negligible in this data.
•	Social media user base showed balanced distribution across genders.
Comparison with Expectations:
It was expected that increased social media exposure might lead to higher suicide rates; however, the opposite trend emerged—suicide rates declined while user counts grew.
Unexpected Outcomes:
•	Equal user count for all genders may reflect synthetic data or normalization, limiting detailed behavioral insights.
•	Steady suicide rate decline suggests multiple other influencing factors (e.g., policy, awareness, support systems).

8. Data Visualizations & Charts
[Insert Dashboard Screenshot Here]
Visuals Used:
•	KPI Cards for summary metrics (e.g., total suicide rate, average users)
•	Line Chart: Suicide rate by year
•	Bar Charts: Facebook and Twitter user counts by year
•	Pie Chart: Suicide rate by gender
•	Combined bar visuals showing user count and suicide rate per gender
Formatting Notes:
•	Consistent blue-green color scheme
•	Simplified labels and clean design for public consumption
•	Balanced layout with central trend charts flanked by demographic insights

9. Recommendations and Observations
Actionable Insights:
•	Future research should incorporate psychological and content-based variables.
•	Engagement quality, not just user count, may be more revealing in assessing social media's influence.
Policy and Academic Suggestions:
•	Educational programs should encourage balanced digital use, especially for vulnerable demographics.
•	More robust datasets should be developed to include content exposure and mental health support access.
Unexpected Observations:
•	Gender balance in suicide rates and social media use was surprisingly even.
•	Data challenges the narrative that increased social media use always correlates with declining mental health.

10. Conclusion
Key Learnings:
•	Suicide rates declined from 2010 to 2019, despite sharp rises in Facebook and Twitter user counts.
•	Gender-based differences were minimal across suicide data and social platform usage.
•	There is no clear evidence from this dataset of a direct, negative correlation between social media use and suicide rates.
Limitations:
•	The dataset lacks regional, behavioral, or emotional context.
•	Equal user counts across genders suggest artificially balanced or anonymized data.
Future Research:
•	Explore impact of content type (positive vs. negative) on mental health.
•	Include age group breakdowns, screen time, and platform-specific behavior patterns.
•	Extend analysis to include crisis intervention data or online sentiment.

11. References & Appendices
References:
•	Dataset: Roles of Social Media on Suicide Analysis.pbix
•	Dashboard Visual: Social Media Suicide Rate.png
•	World Health Organization: Mental Health and Suicide Data
•	Social Media Statistics Reports (2010–2019)
Appendices:
•	Gender-based user count and rate tables
•	Power BI model and DAX formulas
•	Full dashboard visual and interaction notes

