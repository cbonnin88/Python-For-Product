# Python For Product Management

Various projects using Python for Product Analysis and Product Management, ranging from Exploratory Data Analysis to Basic Machine Learning, with a product focus

## [Feature Engagement Scorer](https://www.loom.com/share/cab4d73898ff4414a360839ac8e446ba)
Description: A streamlit web app that calculates user engagement and gives recommended actions

Key Implementations:
- User input: The Product Manager can input the number of logins and new features per week
- Scorer: The app calculates the engagement rate for a user
- Action: The app suggests a call to action based on the user type ('Active', 'At-Risk',' Power User')

## [Product Analyst Metric Converter](https://www.loom.com/share/790146c7f9164b258a944e24c5d12653)
Description: A Streamlit web app that converts standard product management metrics and estimates agile development time.

Key Implementations:
- User input: The Product Analyst selects a conversion category (Revenue, Agile Estimation, or User Engagement) and inputs the base numbers.
- Converter: The app calculates the mathematical translations for MRR/ARR, Story Points to days (factoring in developer seniority), and DAU/MAU proxies.
- Output: The app displays the final estimated metric in a clear, formatted result block for quick reference in product meetings.

## [User Story Generator](https://www.loom.com/share/fe3eb82aa0ce4aa0b6b72f23f3bb1ed9)
Description: A Streamlit web app that facilitates the seamless creation and documentation of structured, data-focused user stories for Data Product Managers.

Key Implementations:
- User input: The Product Analyst inputs standard agile story components (Role, Feature, Benefit) alongside specific data engineering parameters, such as SLA requirements, data quality metrics, and acceptance criteria.
- Document Compiler: The app processes the text inputs sequentially without relying on complex custom functions, dynamically structuring the data into a clean, well-formatted PDF document using the FPDF library.
- Output: The app displays an immediate, formatted preview of the core user story statement on-screen and generates a direct download button to export the final PDF for sharing with data engineering teams.

## [User Feedback Analyzer](https://www.loom.com/share/33fffe93c8f44898b8ef58ce343e3c92)
Description: A Streamlit web application designed for Data Product Managers to interactively filter, analyze, and visualize user feedback from mobile app review datasets using the high-performance Polars DataFrame library in Google Colab.

Key Implementations:
- User input: The Product Manager inputs targeted search keywords (e.g., "bug", "crash", "price") and applies dynamic sidebar filters for specific mobile applications, category tags (such as "fitness" or "running"), and star ratings (1 to 5 stars) via an interactive drag-and-drop CSV uploader or local file detection.
- Data Engine: The app leverages Polars for lightning-fast, memory-efficient data filtering and aggregation to compute real-time product KPIs—including total review volume, average star rating, and critical feedback percentages—without relying on traditional, slower pandas operations.
- Output: The app displays an immediate, high-impact tabular view of user feedback sorted by community thumbs-up counts to highlight top pain points, alongside a customized Altair bar chart with horizontally aligned labels that clearly visualizes the overall star rating distribution.

## [ProductPulse Dashboard](https://www.loom.com/share/46736c75e2004f06af3c7fbd90ae8b65)
Description: An interactive product analytics dashboard built with Polars and Streamlit that provides real-time insights into revenue trends and customer behavioral segments.

Key Implementations:
- Data Ingestion: A flexible upload interface supporting CSV and Excel formats, featuring robust schema handling for complex datasets.
- Data Processing: High-performance data cleaning and feature engineering (KPIs, RFM metrics, and cohort grouping) utilizing Polars' memory-efficient engine.
- Analytics Engine: Automated A/B test statistical analysis (t-test, Mann-Whitney U, CUPED variance reduction) and predictive modeling (Random Forest churn prediction and LTV forecasting).
- Visualization: Interactive revenue funnels and 3D user segment distributions rendered with Plotly.
- Actionable Insights: Rolling Z-score anomaly detection to alert analysts of sudden fluctuations in daily business performance.

## EV Charging App A/B Testing
Description: An interactive web application built with Streamlit and Python that empowers Product Managers to analyze A/B tests, calculate statistical power, and explore customer segments for an EV charging platform.

Key Implementations:
- Data Ingestion: Automated mock data generation that simulates realistic user attributes (country, persona) and behavioral metrics (charging sessions, premium subscriptions) for Western European users.
- Data Processing: Efficient data aggregation and rule-based customer segmentation using Pandas to prepare control and variant group data for direct comparison.
- Analytics Engine: Automated statistical analysis utilizing SciPy and Statsmodels to perform T-tests for continuous data, Z-tests for proportions, and rigorous power calculations for Minimum Detectable Effect (MDE).
- Visualization: Interactive box plots and grouped bar charts rendered with Plotly to clearly illustrate metric distributions and feature performance across different user cohorts.
- Actionable Insights: Clear statistical significance indicators (p-values and absolute/relative differences) and practical analyst tips to help Product Managers make data-driven feature rollout decisions.
