# vamsithota.github.io
# Vamsi's Portfolio
# Project - 1 : Indianapolis Weather Analysis (2020 - 2025)
This project involved analyzing weather trends in Indianapolis from February 2020 to February 2025 using data from the Open-Meteo API. I leveraged R for data acquisition, cleaning, transformation, and visualization, providing valuable insights into temperature, wind speed, and precipitation patterns.

Data Acquisition: I used R packages httr and jsonlite to retrieve daily and hourly weather data, including temperature, wind speed, precipitation, and snowfall, from the Open-Meteo API. The data was parsed from JSON format into a structured data frame for analysis.

Data Cleaning & Transformation: I cleaned the data by handling missing values, converting dates to Date objects, and creating seasonal categories (Spring, Summer, Fall, Winter). This allowed for more targeted analysis, such as identifying temperature extremes and seasonal weather variations.

Exploratory Data Analysis (EDA): I used visualizations such as time series plots, box plots, and bar charts to explore:

Temperature Trends: Revealing seasonal changes, with summer peaks and winter troughs.

Precipitation Distribution: Highlighting variability across seasons, especially intense rainfall in Spring and Summer.

Wind Speed Fluctuations: Identifying wind peaks during winter months and seasonal transitions.

Interactive Dashboard: I developed an interactive dashboard using Quarto and Shiny, enabling users to explore the weather data dynamically. Key features include a date range selector and a weather variable toggle, allowing users to filter data and examine specific weather metrics.

This project showcases my expertise in data wrangling, visualization, and building interactive tools that facilitate data-driven decision-making. It demonstrates the use of R programming and Quarto for creating insightful, real-world applications that make weather data accessible for both technical and non-technical users.

![Data analysis using R - Weather Data](Picture1.jpg) ![Data analysis using R - Weather Data](Picture2.jpg) ![Data analysis using R - Weather Data](Picture3.jpg)

# Project - 2 : HR Analytics Dashboard : PowerBi
Developed a comprehensive HR Analytics Dashboard in Power BI to provide data-driven insights into workforce management. The dashboard integrates multiple datasets to track employee demographics, attrition trends, hiring patterns, performance analytics, and workforce diversity.

Key Features & Functionalities:
Employee Demographics & Diversity Analysis: Visualized workforce distribution based on age, gender, department, and experience levels to support HR in building a diverse and inclusive workplace.
Attrition & Retention Insights: Identified trends in employee turnover, analyzed reasons for attrition, and provided predictive insights to improve retention strategies.

Performance & Productivity Metrics: Tracked employee performance based on KPIs, enabling HR teams to identify top performers and areas for improvement.

Recruitment & Hiring Trends: Monitored hiring rates, department-wise recruitment efficiency, and new hire success rates to optimize hiring processes.

ETL & Data Processing: Implemented data extraction, transformation, and loading (ETL) pipelines to clean and preprocess HR data for accurate reporting.

Advanced DAX Measures & Calculations: Used DAX functions to create custom metrics for turnover rates, average tenure, and employee satisfaction scores.

Interactive & Dynamic Visualizations: Designed filter-enabled reports, allowing users to drill down into specific departments, roles, and time frames.

Automation & Real-time Updates: Integrated with HR databases and Excel sheets to enable automated data refreshes and real-time workforce monitoring.

This dashboard serves as a decision-support tool for HR teams, helping them identify workforce trends, streamline recruitment, and enhance employee engagement strategies. It empowers leadership with data-driven insights to optimize talent management, workforce planning, and overall HR efficiency.

![Data analysis using PowerBI - HR](HR-Dashboard1.jpg) ![Data analysis using PowerBI - HR](HR-Dashboard2.jpg)

# Project - 3 : Data Professionals Summary : PowerBi
In this project, I developed an interactive dashboard designed to extract valuable insights from a dataset of over 50,000 survey responses from data professionals. The dashboard provides a comprehensive overview of key trends in salary, career transitions, programming language preferences, and job satisfaction.

Key Insights & Features:

Salary Analysis:
Visualized salary distributions across different roles such as Data Scientist, Data Engineer, and Data Architect. Enabled comparisons of salary ranges across various countries including the United States, Canada, the UK, India, etc. Offered gender-based salary insights to help identify potential pay disparities. 
Career Transition & Challenges:
Analyzed responses regarding the difficulty of entering the data field, categorizing the feedback into levels ranging from Very Easy to Very Difficult. Provided aspiring data professionals with a realistic view of the industry’s entry challenges.
Programming Language Preferences:
Highlighted the most frequently used programming languages among data professionals, with Python leading the list, followed by R, SQL, C/C++, JavaScript, and Java. Job Satisfaction & Work-Life Balance
Evaluated satisfaction metrics such as salary happiness (with an average rating of 4.33 on a 1-10 scale) and work-life balance (average rating of 5.92). Delivered a detailed snapshot of overall job satisfaction within the data field.
This dashboard not only brings clarity to the current trends and challenges within the data industry but also serves as an essential tool for both seasoned professionals and newcomers aiming to navigate their career paths in data.

![Data analysis using PowerBI - HR](Datasurvey.jpg)

# Project - 4 : LEGO Themed Interactive Dashboard – Enhancing Product Discovery with Data

In this project, I designed an advanced Power BI dashboard to interactively analyze and explore LEGO product data, encompassing over 4,000 rows of records. The solution leverages dynamic filtering, robust DAX measures, custom visuals, and intuitive navigation features to elevate the user experience.

Key Features & Techniques:
Price-Based Filtering:
Implemented a numeric range parameter (0–850 in increments of 5) combined with a slicer and DAX measure to dynamically filter LEGO sets by price.
Interactive Image Tooltips:
Enabled hover-based tooltips that display images of LEGO sets, providing a richer visual context during exploration.
Custom Reset Filters:
Created bookmarks and button actions with customized hover and press states, allowing users to easily reset all applied filters.
Decomposition Tree Analysis:
Integrated a decomposition tree to break down Total Sets by category, theme group, theme, and set name, complete with navigation buttons for seamless data exploration.
Data Modeling & Cleaning:
Connected to a LEGO sets CSV file, streamlined the data by removing unnecessary fields, correcting data types, and filtering out incomplete records.
Advanced Slicers & Interactions:
Developed slicers for theme group, theme, and age range, enabling refined selections while ensuring that top-level KPI cards remain unaffected.
KPI Cards & Measures:
Designed card visuals to display essential insights such as Total Sets, Average Pieces per Set, and Average Price using precise DAX measures.
Conditional Formatting:
Applied custom formatting by defining specific Age Range categories (Over 18, 10–17, 5–9, 1–4) and Price Range labels (from $ to $$$$$) to enhance data readability.
Detailed Set View:
Crafted a dedicated report section that provides detailed information on product attributes (name, image, price, year, pieces, age), utilizing placeholder values when multiple sets are selected.

![Data analysis using PowerBI - HR](lego.jpg)
