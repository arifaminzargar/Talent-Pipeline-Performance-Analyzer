**📊 Talent Pipeline Performance Analyzer – From Data Cleaning to Business Insights

I recently built a Power BI dashboard to analyze recruitment performance, starting from raw data cleaning to deriving actionable insights.

🔧 Data Creation & Cleaning Approach:

Dropped messy columns (Misc note, Candidate ID) to avoid CSV contamination.

Standardized inconsistent values in Current Stage Column using a custom column (Current Stage1) and later renamed it to current stage.

Filled blanks in Current stage column  using related fields (offer date, join date, offer value), and replaced remaining with “Unknown” to form  Current stage filled column.

Created a Stage Order table to define hiring flow (Screening → L1 → L2 → Final → Offered → Joined) and applied Sort by Column for accurate funnel visualization.

Cleaned Client Name formatting using split/merge in Power Query.

Added dummy revenue data for forecasting trends.

💡 Key Insights from the Dashboard:

✅Offer to Join Ratio (50.7%):  Only about half of the candidates who receive an offer join.
Recommendation:  Address reason for offer declines, review the competitiveness of CTC offered, experience appreciated.

✅ Candidate Funnel – Significant mid-stage drop-offs (Screening/L1 → L2 → Final)
Recommendation:There should be focus on optimizing candidate experience and conversion in mid-process stages (L1, L2, Final)to reduce attrition and increase the total number of candidates progressing to offer and join statuses.  There should be detailed exit/interview feedback to address any mid-funnel bottlenecks.

✅ Revenue by Client :Engagement with top clients for continued growth should be deepened and focus on development for clients with lower revenue contribution.

✅ Revenue Forecast:   Revenue forecast shows an upward forecast trend but monthly revenue fluctuates significantly.
Recommendation: Stabilize recruitment and onboarding pipelines to convert forecasted revenues to actuals.


🚀 Impact:
This dashboard not only tracks recruitment stages but also ties them directly to business impact (revenue), enabling better decision-making across sourcing, client engagement, and pipeline management.
