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
