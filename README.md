# stack_overflow_survey_analysis
In this project, we are going to analyze 2020 Stack Overflow Developer Survey. 
We are going to  examine all aspects of the developer experience from career satisfaction and job search to education and opinions on open source software.
We are also going through the most popular programming languages and we are analyzing the salaries per country and depending on the qualifications of the developper. 

The dataset we are using is provided by: https://insights.stackoverflow.com/survey
With nearly 65,000 responses fielded from over 180 countries and dependent territories.
The first challenge we are facing is improving the data quality. Since the data is collected from a survey, there aremany unusered questions, which means null values. 
Also, we could be tricked by the salaries. So, we will have certaintly outliers. 

Before cleaning the dataset, we need to understand it well. 

## Description of the data: 
We have two files:
1. survey_results_public.csv - CSV file with main survey results, one respondent per row and one column per answer
2. survey_results_schema.csv - CSV file with survey schema, i.e., the questions that correspond to each column name

The survey was fielded from February 5 to February 28, 2020.
In order to achieve the work, we are going through these steps: 
1. Loading data
2. Assessing of data
3. Data Cleaning
4. Exploratory data analysis (EDA)
5. Conclusion
