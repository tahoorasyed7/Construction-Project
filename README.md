# Construction Project Management Report  -Dashboard

###Dashboard Link:https://app.powerbi.com/groups/e0654e44-a843-419e-a279-9fc5915d934d/dashboards/1fa14780-3755-46cc-8115-f010e134f600?experience=power-bi

## Problem Statement

 This dashboard is designed to help construction companies and project managers track and analyze project performance, resource utilization, and document management in real-time. By leveraging key metrics, stakeholders can efficiently monitor project progress, detect potential delays, and ensure compliance with documentation requirements.

Through different metrics, this dashboard provides insights into project timelines, costs, resource allocation, and document tracking, helping teams to streamline processes and optimize decision-making. It also identifies potential delays in project execution, allowing proactive measures to be taken.

Since a significant percentage of projects face cost overruns and schedule delays, this dashboard aims to provide actionable insights that help in mitigating risks and ensuring smooth project completion.

### Key Challenges and Objectives:
Steps followed

Step 1: Load data into Power BI Desktop from multiple sources (Excel, CSV, JSON, MySQL).

Step 2: Open Power Query Editor and review "Column Distribution," "Column Quality," and "Column Profile" to check for data consistency.

Step 3: Handle missing values, remove duplicates, and clean the dataset to ensure accuracy in project insights.

Step 4: Split the "Location" field into City and Country for effective geographic analysis.

Step 5: Format date fields to ensure proper time-based analysis of project timelines.

Step 6: Select an appropriate theme for dashboard consistency.

Step 7: Create necessary visual filters (slicers) for easy data navigation, including filters for:

Project Status (Ongoing, Completed, Delayed)

Project Manager

Location

Document Type

Contractor

Project Category

Step 8: Add card visuals to display Total Projects, Total Budget, Total Costs, and Number of Documents Managed.

Step 9: Create a bar chart to visualize project completion status (On-time, Delayed).

Step 10: Utilize map visualizations to represent project locations and revenue distribution across regions.

Step 11: Add a table to track documents uploaded per project, categorized by document type.

Step 12: Create calculated columns and measures for key metrics

Total Cost: Sum of all expenditures for each project.

Total Revenue: Calculated as project value per contract.

Profitability Index: (Total Revenue - Total Cost) / Total Cost.

Average Document Uploads per Project.

Percentage of Projects Completed On-Time.

Monthly Trend in Project Completion.

Step 13: Add a DAX measure to dynamically display project progress:

Project Progress = DIVIDE([Completed Tasks], [Total Tasks], 1)

Step 14: Add text boxes to display the Construction Company Name and Project Tagline.

Step 15: Utilize Gantt charts for project timeline tracking, line charts for trend analysis, Guage chart and card visuals for alerts, emails, and subscriptions to enhance monitoring capabilities.

Step 16: Publish the report to Power BI Service for real-time monitoring and access across teams.


 The report was then published to Power BI Service.
 
# Snapshot of Dashboard (Power BI Service)




Conclusion

This Construction and Document Tracking Dashboard provides real-time project visibility, ensuring teams can monitor project timelines, costs, and documentation compliance effectively. The insights generated help optimize resources, reduce delays, and improve profitability. 🚀








