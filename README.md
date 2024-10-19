# Data Analysis Project: Capstone on Tech Workforce and Compensation Trends

This repository contains Python scripts and a detailed analysis of workforce demographics, compensation, and trends in the technology industry. The data is sourced from a large survey, and the results focus on key factors such as salary distributions, programming language preferences, platform usage, and database trends.

## Table of Contents
- [Project Description](#project-description)
- [Project Structure](#project-structure)
- [Data Collection and Preprocessing](#data-collection-and-preprocessing)
- [Key Findings](#key-findings)
- [Requirements](#requirements)
- [Usage Instructions](#usage-instructions)
- [Visualization and Insights](#visualization-and-insights)
- [Conclusion](#conclusion)
- [Author](#Author)

## Project Description

This project analyzes survey data from over 11,000 tech professionals to explore trends in salary, job satisfaction, platform usage, and programming language preferences. After data cleaning, including removing duplicates and handling missing values, the analysis focuses on 1,008 respondents to provide insights into compensation patterns and technology trends.

## Project Structure

The project is divided into the following scripts:
- **Part 1: Data Collection** (`Part 1 Data Collection.py`)  
  Retrieves the raw data, performs initial exploration, and prepares the dataset for further analysis.
- **Part 2: Data Wrangling and Exploratory Analysis** (`Part 2 Data wrangling and exploratory analysis.py`)  
  Handles data cleaning, duplicate removal, missing values, and normalization of compensation data.
- **Part 3: Data Visualization** (`Part 3 Data visualization.py`)  
  Generates visualizations to show trends in compensation, age, and other factors.

Additionally, you can find PDF summaries of the results in the following documents:
- **Summary of Results** (`summary of results.pdf`)
- **Presentation of Results** (`Presentation of results.pdf`)

## Data Collection and Preprocessing

### Dataset
The dataset was retrieved from an online source and contains information such as:
- Respondents’ age, gender, and country.
- Compensation details (annual, monthly, weekly salaries).
- Employment type and coding experience.
- Preferred programming languages and platforms.

### Data Preprocessing
- **Initial Dataset**: 11,552 entries.
- **After Cleaning**: 1,008 entries remained after removing duplicates and rows with missing data.
- **Compensation Normalization**: Salaries were normalized to an annual basis for comparison.
- **Outlier Handling**: Extreme outliers in compensation were excluded to focus on realistic salary ranges.

## Key Findings

1. **Demographics**:
   - Median age of respondents: 29 years.
   - Median salary: $52,704 (with 50% earning between $24,060 and $85,574).
   - Gender distribution: 10,480 men, with a minimal salary gap between male and female respondents.

2. **Programming Language Trends**:
   - Most commonly used languages: **HTML/CSS**, **Bash/Shell/PowerShell**, and **JavaScript**.
   - Languages respondents most want to learn: **JavaScript**, **Python**, and **TypeScript**.
   - **Go** is emerging as a language for high-performance backend systems.

3. **Platform and Database Trends**:
   - Dominant platforms: **Docker**, **Linux**, and **AWS**.
   - Most commonly used databases: **MySQL**, **Microsoft SQL Server**, and **MongoDB**.
   - Future interest in databases: **PostgreSQL** and **MongoDB** lead, followed by **Elasticsearch** and **Redis** for specialized needs.

## Requirements needed for analysis in python

- Python 3.x
- Libraries:  
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `docx`
  - `sqlite3`

You can install all necessary dependencies using:
```
-pip install 
```



## Usage Instructions

1. Clone the repository:
```
git clone <repository_url>
cd <repository_directory>
```
2. Run each script to perform data collection, wrangling, and visualization:
```
python "Part 1 Data Collection.py"
python "Part 2 Data wrangling and exploratory analysis.py"
python "Part 3 Data visualization.py"
```
3. View the final results in the generated Part_5_Presentation_of_results.docx document or the PDF summaries included in the repository.

## Visualization and Insights
The project includes several visualizations, such as:

- Salary Distribution: Histogram showing the distribution of annual salaries.
- Age and Salary Correlation: Scatter plot showing the correlation between age and compensation.
- Database Preferences: Pie charts illustrating databases respondents wish to learn in the future.
  
These visualizations provide key insights into the demographics and compensation patterns within the tech industry.

## Conclusion

### Conclusion (Extended)
This analysis of workforce demographics and technology trends highlights several key factors influencing the tech industry.

### Demographics and Compensation:
The workforce in this analysis skews young, with a median age of 29 years. Half of the respondents earn between $24,060 and $85,574 annually, and while the average salary is approximately $59,883, the median salary of $52,704 provides a more accurate view of typical compensation due to the influence of outliers. Notably, there is minimal gender disparity in compensation, although the dataset itself is heavily male-dominated. The correlation between age and salary (0.40) suggests that, generally, older respondents tend to earn more, with salary growth peaking in the mid-30s to early 40s, before plateauing around age 50.

### Programming Language Trends:
The most used languages currently are HTML/CSS, Bash/Shell/PowerShell, and JavaScript, while the most desired languages for the upcoming year are JavaScript, Python, and TypeScript. These trends indicate that full-stack developers and those with skills in versatile and modern programming languages, especially JavaScript, will continue to be in high demand. The growing interest in Go signals a trend toward performance-oriented backend development, particularly in areas that require efficiency and scalability.

### Platform and Database Trends:
Docker, Linux, and AWS dominate the current platform landscape, reflecting the continued trend toward containerization and cloud-native development. The increasing popularity of Kubernetes suggests that developers with skills in orchestration and scalability will be well-positioned in the market. In terms of databases, the demand for PostgreSQL, MongoDB, Elasticsearch, and Redis shows a clear shift toward open-source and NoSQL solutions, which offer flexibility and scalability. This shift reflects the growing importance of handling large-scale, unstructured data, particularly in industries like big data and IoT.

### Implications for Developers:
To thrive in this evolving landscape, developers must focus on upskilling in both modern programming languages and cloud infrastructure technologies. JavaScript, Python, and TypeScript will remain crucial, while Go represents an emerging skill for developers looking to work in high-performance back-end systems. In terms of infrastructure, mastering Docker, Kubernetes, and cloud platforms will be essential as businesses increasingly adopt multi-cloud and containerized environments. Finally, expertise in PostgreSQL, MongoDB, and related database technologies will be critical for handling the growing demands of scalable and real-time data applications.

### Final Thoughts:
The findings in this analysis underscore the growing complexity of the tech industry, where adaptability and a well-rounded skill set are paramount. Organizations should focus on fostering diverse and highly skilled teams to keep pace with the rapid technological advancements in programming, cloud infrastructure, and database management. By leveraging these trends, both organizations and developers can position themselves to excel in a rapidly changing industry.

## Author

Kalab Alemayehu
