# Python For Product Management

Various projects using Python for Product Analysis and Product Management, ranging from Exploratory Data Analysis to Basic Machine Learning, with a product focus

## StreamFlix - EDA
Description: Exploratory Data Analysis using Polars and Plotly to uncover customer usage and the churn rate of different customer types

## MusicNow Analytics
Description: The goal of this project is to process raw event logs and transform them into actionable product insights using modern Python data manipulation and visualization libraries.

Key Implementations:
- Synthetic Data Generation: Engineered a custom dataset of user events (including song plays, logins, ad clicks, and premium upgrades) to simulate real-world user behavior.
- Data Cleaning Pipeline: Utilized Polars to cast date strings into proper datetime objects, handle missing values, and filter relevant event streams for accurate aggregation.
- Core Product Metrics: Calculated and visualized Daily Active Users (DAU), Total Daily Streams, and Average Listen Time per Day using Plotly line and bar charts.
- Advanced Analytics: Executed a Day-1 cohort retention analysis and calculated overall free-to-premium conversion rates to evaluate user engagement and monetization.

## Feature Engagement Scorer
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

## User Story Generator
Description: A Streamlit web app that facilitates the seamless creation and documentation of structured, data-focused user stories for Data Product Managers.

Key Implementations:
- User input: The Product Analyst inputs standard agile story components (Role, Feature, Benefit) alongside specific data engineering parameters, such as SLA requirements, data quality metrics, and acceptance criteria.
- Document Compiler: The app processes the text inputs sequentially without relying on complex custom functions, dynamically structuring the data into a clean, well-formatted PDF document using the FPDF library.
- Output: The app displays an immediate, formatted preview of the core user story statement on-screen and generates a direct download button to export the final PDF for sharing with data engineering teams.
