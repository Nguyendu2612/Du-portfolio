# Dashboard's Portfolio
*❗For confidentiality reasons related to previous projects, the brand data shown is fictional and for illustrative purposes only. Consequently, insights derived from this data may not reflect actual market realities.*
# 📊Project 1: Competitor Analysis Dashboard
# ================================
### Project Workflow & business tasks
<img src="Image/Pharmacity.png" alt="Project Workflow & business tasks" width="600" style="border-radius:20px;">
## *Dashboard:*
### Log-in Page
<img src="Image/Fama/Begin.png" alt="Log-in Page" width="600" style="border-radius:20px;">
### Analytics Page
<img src="Image/Fama/1.png" alt="Analytics Page" width="600" style="border-radius:20px;">
### Detailed Page
<img src="Image/Fama/1.2.png" alt="Detailed Page" width="600" style="border-radius:20px;">
### Tooltip Page
<img src="Image/Fama/1.3.png" alt="Tooltip Page" width="600" style="border-radius:20px;">
# 🛍️Project 2: Retail Basket Analytics
# ================================
### Project Workflow & business tasks
<img src="Image/Lotte.png" alt="Project Workflow & business tasks" width="600" style="border-radius:20px;">
## *Dashboard:*
<img src="Image/Lotte.pngImage/Lotte/1.png" alt="" width="600" style="border-radius:20px;">
<img src="Image/Lotte.pngImage/Lotte/2.png" alt="" width="600" style="border-radius:20px;">
<img src="Image/Lotte.pngImage/Lotte/3.png" alt="" width="600" style="border-radius:20px;">
# 🏷️Project 3: Store Promotion Report
# ================================
## *Project Overview:*
Collected store-level data through mystery shopping: surveyed sellers on Milo SKU prices (per client brief) and recorded whether POSM materials (standee, booth, pallet) were present.

## *My Role:*

- Built the dimensional model and relationships for the dashboard.
- Wrote DAX measures to compute KPIs and surface insights.
- Leveraged tooltips for quick, in-context data views.

## *Output:*
- Presence rates of Milo SKUs and POSM types across stores.
- Sellers’ perceptions of Milo products compared with market alternatives.

## *Dashboard:*
### Log-in Page
<img src="Image/Milo/1.png" alt="Log-in Page" width="600" style="border-radius:20px;">
### Summary Page
<img src="Image/Milo/2.png" alt="Summary Page" width="600" style="border-radius:20px;">
### Detail Page
<img src="Image/Milo/3.png" alt="Detail Page" width="600" style="border-radius:20px;">
### Map POSM distribution Page
<img src="Image/Milo/4.png" alt="MAP Page" width="600" style="border-radius:20px;">
# 🔥Project 4: Users Uploading Streak Dashboard
# ================================
## *Project Overview:*
This is a small task within our team's project focused on analyzing user shopping behavior through uploaded receipts. The dashboard will analyze the data and identify panelists meeting certain criteria, such as:
- *Uploading more than 10 receipts within 30 days*
- *Participating for more than 7 days*
- *Having a rejection rate below 20%*
- *Not being included in the blocked respondents list*

## *My Role:*

- Received the requirements and conducted detailed discussions to fully understand the teammate's needs.
- Requested data sourcing from the team via Power BI data flows (from the team's database). *(Due to time constraints, I have not yet had the opportunity to thoroughly learn about these data flows.)*
- Utilized Power Query to clean and format data for analysis (e.g., filtering out blanks in the Phone field, creating a dim_calendar table, sorting by MonthYear or WeekNum).
- Employed DAX functions to analyze data according to specified criteria (using Row Context).

## *Output:*
Generated a monthly list of qualified panelists within specified time periods.
## *Dashboard:*
### First Version
This version uses HTML to customize streak calculation, displaying streaks by week within specific timeframes. However, since users need to download Excel files, it must revert to raw data.
<img src="Image/Panelist/1.png" alt="First Version" width="600" style="border-radius:20px;">
### First Version - QC Page
This is a drill-through page used for quality control, allowing checks on previously selected panelists.
<img src="Image/Panelist/2.png" alt="First Version - QC Page" width="600" style="border-radius:20px;">
### Second Version
This page has been adjusted according to user requirements and is currently filtered to display all panelists.
<img src="Image/Panelist/3.png" alt="Second Version" width="600" style="border-radius:20px;">
### Second Version - Filtered
This page is filtered to show panelists with the highest streaks in June.
<img src="Image/Panelist/4.png" alt="Second Version - Filtered" width="600" style="border-radius:20px;">
This is the page where users requested additional conditions to calculate streaks for individual panelists
<img src="Image/Panelist/5.png" alt="Second Version - Filtered" width="600" style="border-radius:20px;">

