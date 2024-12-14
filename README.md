# COVID19-Data-Analysis-Project

# COVID-19 Outcomes by Testing Cohorts: Cases, Hospitalizations, and Deaths
This project focuses on analyzing and visualizing COVID-19 data to uncover trends and actionable insights. By leveraging SQL, Python, and interactive visualizations, we provide a user-friendly platform for understanding key metrics such as the number of tests, confirmed cases, hospitalizations, and deaths. The findings support evidence-based public health decision-making and resource allocation.

## Project Overview
The project was inspired by the rise in COVID-19 cases from recent variants (e.g., JN1 as of December 2023). The goal is to conduct a comprehensive analysis of the COVID-19 Outcomes by Testing Cohorts dataset, enabling users to explore temporal trends and critical health outcomes. By implementing an interactive interface, users can dynamically analyze data to gain valuable insights for pandemic management.

## Dataset Details
- Source: !([NYC Open Data - COVID-19 Outcomes](https://data.cityofnewyork.us/Health/COVID-19-Outcomes-by-Testing-Cohorts-Cases-Hospita/cwmx-mvra)
- Size: 176,000 rows and 6 columns
- Columns:
  - *extract_date:* Date of specimen extraction.
  - *specimen_date:* Date of specimen collection or diagnosis.
  - *Number_tested:* Count of individuals tested for COVID-19.
  - *Number_confirmed:* Count of confirmed COVID-19 cases.
  - *Number_hospitalized:* Count of confirmed cases hospitalized.
  - *Number_deaths:* Count of confirmed cases that resulted in death.
 
 ## Project Approach
- **Data Parsing and Normalization:**
   - Parsed raw data from a CSV file using Python.
   - Normalized data into three SQL tables: DATEINFO, TESTINFO, and CASESINFO.
- **Database Integration**
  - Connected to SQL databases for efficient data management.
  - Loaded and organized normalized data for query execution.
- **Exploratory Data Analysis (EDA):**
  - Conducted EDA using Python libraries to uncover patterns in testing, confirmed cases, hospitalizations, and deaths.
  - Designed an interactive interface with ipywidgets for dynamic data exploration.
- **Visualizations:**
  - Created pie charts, box plots, line plots, and bar charts for intuitive data representation.
  - Focused on highlighting proportions, distributions, and trends over time.

 ## Conclusion
 The analysis provides valuable insights into COVID-19 trends, identifying periods of increased testing, outbreaks, and patterns in health outcomes. Interactive visualizations enable users to better understand data distributions and proportions, supporting informed public health decisions. This project serves as a tool for dynamic exploration of pandemic data and resource allocation strategies.
