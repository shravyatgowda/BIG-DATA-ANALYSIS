# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SHRAVYA T

*INTERN ID*: CT04DZ1893

*DOMAIN*: DATA ANALYST

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

Task Description

The objective of this Task was to perform big data analysis using tools such as PySpark or Dask to demonstrate the ability to process and analyze large datasets efficiently. The dataset size requirement was around 10,000 rows to illustrate scalability and analytical capabilities. The aim was to not only process the data but also derive meaningful insights that could inform decision-making in a business context. This task is part of Codtech’s Data Analyst Internship, where emphasis is placed on practical, real-world skills in handling large volumes of data.

Task Performed

For this task, a synthetic dataset with 10,000 rows was created to simulate user interaction data in an e-commerce-like environment. The dataset contained fields such as:

1. user_id – Unique identifier for each user

2. timestamp – Date and time of the event

3. event_type – Type of user action (click, view, purchase, signup, refund)

4. value – Monetary value for purchase transactions

5. category – Product category (electronics, clothing, books, etc.)

6. country – Country of the user

The following steps were performed:

1. Data Creation – A synthetic dataset was generated programmatically using Python’s pandas and numpy.

2. Data Loading – The dataset was read using Dask for scalability. Pandas was used as a fallback for environments without Dask installed.

3. Data Cleaning & Preparation – Missing values in value were replaced with 0, and relevant date-time components (date, hour) were extracted for time-based analysis.

4. Aggregations – Metrics were calculated, including daily event counts, purchase counts, and total revenue by country.

5. Category-Level Analysis – Conversion rates from view to purchase were computed for each product category.

6. Visualization – A bar chart showing the top countries by total revenue was created using Matplotlib.

7. Exporting Results – Summary CSV files (daily events and purchases by country) were saved for further reporting.

   Tools Used
   
1. Dask – For scalable, parallelized data processing.

2. Pandas – For data handling when dataset size was manageable without distributed computing.

3. NumPy – For numerical data generation and manipulation.

4. Matplotlib – For creating a simple visualization of the results.

5. Python – Main programming language for data processing and analysis.

Editor/Platform Used

The task was developed and tested in Jupyter Notebook, a popular environment for data science and analytics projects. This environment allowed step-by-step code execution, inline visualizations, and Markdown documentation for clear explanation.

Applicability of This Task

The skills and methodology demonstrated in this task are applicable to several real-world contexts:

1. E-commerce Analytics – Tracking user interactions, conversion rates, and revenue by region.

2. Digital Marketing – Identifying high-performing categories or geographies to target in campaigns.

3. Business Intelligence (BI) – Producing reports that help in data-driven decision-making.

4. Big Data Environments – Using scalable frameworks like Dask or PySpark to process millions of records beyond the limits of single-machine pandas workflows.

5. Operational Monitoring – Tracking daily events to detect unusual spikes or drops in activity.

This project showcases the ability to not only manage large datasets but also to extract actionable insights, making it a valuable skill set for roles in Data Analytics, BI, and Data Engineering.




Visualization – A bar chart showing the top countries by total revenue was created using Matplotlib.

Exporting Results – Summary CSV files (daily events and purchases by country) were saved for further reporting.
