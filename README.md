# Healthcare-Data-Patient-Wait-List

##1.📌 Project Title / Headline
 
Healthcare Analytics: An end-to-end Power BI project built using real-world healthcare data to analyze and monitor patient waiting lists across specialties, age profiles, and treatment types from 2018–2021. Covers the full BI development cycle from requirement gathering to deployment, with insights designed to support hospital administrators and health policymakers.

3. Short Description / Purpose
   
This project showcases a complete end-to-end Power BI dashboard development lifecycle using publicly available healthcare data on patient waiting lists (2018–2021). It covers every step from requirement gathering, data transformation, modeling, to dashboard design and deployment. The interactive report enables stakeholders to monitor waitlist trends, compare inpatient/outpatient metrics, and perform deep dives by specialty and age profile—supporting data-driven decisions in the healthcare sector.

5. Tech Stack
List the key technologies used to build the dashboard.
The dashboard was built using the following tools and technologies:
• 📊 Power BI Desktop – Main data visualization platform used for developing the interactive dashboard and reports.
• 📂 Power Query – Data transformation and cleaning layer used to reshape, append, and standardize inpatient and outpatient datasets.
• 🧠 DAX (Data Analysis Expressions) – Used for creating calculated measures, dynamic titles, conditional messages, and key performance indicators (KPIs).
• 📝 Data Modeling – Relationships established between tables (e.g., All_Data, Specialty Mapping) to enable filtering, drilldowns, and efficient aggregation.
• 📁 File Format – .pbix for Power BI dashboard development, .csv/.xlsx for data inputs, and .png for custom visual backgrounds and dashboard previews.
• 🎨 Canva / PowerPoint – Used for designing custom report backgrounds and enhancing dashboard aesthetics.

6. Data Source
The dataset contains monthly patient waiting list data collected by NHS England from 2018 to 2021. It captures both Inpatient and Outpatient categories across multiple medical specialties and includes the following key fields:

📅 Archive Date – Monthly reporting period
🏥 Case Type – Inpatient / Outpatient
🧑‍⚕️ Specialty Name – Detailed clinical specialty (e.g., Cardiology, General Surgery)
⏱ Time Band – Duration of patient wait times (e.g., 0–18 weeks, 18+ months)
👶 Age Profile – Age group of the patient (e.g., 0–17, 18–64, 65+)
🔢 Total – Number of patients waiting under each combination of filters

5. Features / Highlights
• Business Problem
The growing demand for healthcare services in the UK has led to long waiting times for both inpatient and outpatient treatments. NHS administrators and policymakers often struggle to quickly assess the scale, trends, and distribution of patient waiting lists across specialties and age groups.

Key challenges include:
Which specialties are facing the longest delays?
How have waiting lists changed over time?
Are certain age groups or case types more affected?
How can we optimize resources and reduce bottlenecks?

• Goal of the Dashboard
To deliver an interactive Power BI dashboard that:
Enables healthcare decision-makers to explore trends in patient wait times from 2018 to 2021
Highlights problem areas across specialties, age groups, and time bands
Supports strategic planning and resource allocation
Provides KPI monitoring, drill-down analysis, and visual storytelling for better insights

• Walkthrough of Key Visuals
KPI Cards (Top Row)
🔹 Latest Month Wait List – Total patients currently waiting
🔹 Previous Year Comparison – Wait list count 12 months prior
🔹 Toggle-based Average/Median – Users can switch between average or median values for customized views

Calculation Method Toggle (Button Slicer)
Interactive switch between Average and Median calculations across all visuals

Donut Chart (Waitlist by Specialty Group)
Visualizes the distribution of total waiting patients by grouped medical specialty

Clustered Column Chart (Time Trend)
Monthly wait list trend for Inpatients and Day Cases vs Outpatients, filtered by case type

Top 5 Specialties (Multi-Row Card)
Shows the top 5 specialties with the highest number of patients on the waitlist

Line Charts (Historical Trends)
Separate line charts for Inpatient/Day Case and Outpatient waitlist trends over time

Slicers (Filters)

🔘 Date
🔘 Specialty
🔘 Case Type
🔘 Age Profile

Detailed Page (Matrix View)
A tabular view that shows detailed breakdown by Archive Date, Specialty, Age Profile, Time Band, and Case Type

Tooltip Page (Interactive Hover Tooltips)
Custom tooltip with a bar chart and KPI card that appears when hovering over line charts to show context-specific breakdown

• Business Impact & Insights
✅ Performance Monitoring: Easily track trends in patient wait times over months and years to monitor system performance.
✅ Bottleneck Identification: Quickly identify overburdened specialties (e.g., Orthopedics, ENT) or time bands (e.g., 18+ months).
✅ Targeted Resource Allocation: Insights can guide targeted funding, staffing, or infrastructure changes in the most affected areas.
✅ Age-Based Planning: Age-profile filters help in planning pediatric vs. geriatric care strategies more effectively.
✅ Data-Driven Policy Decisions: The dashboard empowers health policymakers with accurate, real-time insights for planning and operational improvements.

6. Screenshots / Demos
