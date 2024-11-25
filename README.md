# PYTHON
Python
Python is a programming language widely used by Data Scientists.
Python has in-built mathematical libraries and functions, making it easier to calculate mathematical problems and to perform data analysis.
Python Libraries
Pandas - This library is used for structured data operations, like import CSV files, create dataframes, and data preparation
Numpy - This is a mathematical library. Has a powerful N-dimensional array object, linear algebra, Fourier transform, etc.
Matplotlib - This library is used for visualization of data.
SciPy - This library has linear algebra modules
Data Analysis with Python 
Data Analysis is the technique of collecting, transforming, and organizing data to make future predictions and informed data-driven decisions. It also helps to find possible solutions for a business problem. There are six steps for Data Analysis. They are: 
•	Ask or Specify Data Requirements
•	Prepare or Collect Data
•	Clean and Process
•	Analyze
•	Share
•	Act or Report
What is Exploratory Data Analysis?
Exploratory Data Analysis is an approach to data analysis outlining features of the data, testing assumptions, and checking for anomalies before formal modelling. It's about visualizing, summarizing and interpreting the information hidden in rows and columns of data.
Data Set
The dataset from ABC company, consisting of 458 rows and 9 columns. The company requires a comprehensive report detailing information about their employees across various teams. The dataset contains the following columns:
•	Name: Employee name.
•	Team: The team the employee belongs to.
•	Number: Likely an ID 
•	Position: The role within the company.
•	Age: Age of the employee.
•	Height: Employee height (wrong format)
•	Weight: Employee weight in numeric form.
•	College: College attended (with missing values).
•	Salary: Employee salary (with some missing values).
The analysis process includes data preprocessing, statistical analysis, and graphical representations to communicate findings effectively.

Objectives
•	Preprocess the dataset to ensure data consistency and integrity.
•	Perform detailed analysis to answer specific business questions.
•	Visualize findings using graphs and charts for clarity.
•	Present insights and trends identified during the analysis.
Preprocessing Steps
•	Height Correction: Replaced inconsistent height data with random integers ranging from 150 to 180 cm.
•	Missing Salary Data: Handled missing values in the "Salary" column by replacing them with the median salary of the dataset.
•	Data Validation: Ensured all columns contain consistent and valid data for analysis

Data cleaning  
Data cleaning refers to the process of removing unwanted variables and values from our dataset and getting rid of any irregularities in it.
•	The "Height" column has been successfully updated with random integers between 150 and 180. 
There are missing values in the dataset:
•	College: 84 missing values – it’s not essential for the given tasks
•	Salary: 11 missing values - replaced missing value with mean value
Analysis Tasks
•	Team Distribution: Calculated the distribution of employees across teams and their percentage relative to the total workforce.
•	Position Segregation: Grouped employees by their positions.
•	Predominant Age Group: Identified the most common age group among employees.
•	Highest Salary Expenditure: Determined which team and position contribute the most to salary costs.
•	Correlation Analysis: Investigated the relationship between age and salary, representing findings visually.

`
Graphical Representations
For each analysis task, the following visualizations were created:
•	Bar Chart: Showing employee height distribution & Showing employee distribution across teams
•	Pie Chart: Displaying the percentage split of positions.
•	Count plot: Highlighting the predominant age group.
•	Scatterplot: Illustrating salary expenditure by team and position.
•	Scatter Plot: Depicting the correlation between age and salary.
Data Story: Key Insights and Observations
The analysis of the ABC Company employee dataset revealed several critical trends and patterns that provide a deeper understanding of the organization's structure and financial distribution:
•	Employee Distribution Across Teams- 
The analysis showed that team sizes are not the same. Some teams are much bigger than others. The largest team has a big share of the employees, which shows it plays an important role in the company. On the other hand, smaller teams might handle specialized tasks or have fewer resources.

•	Job Roles
Employees are spread across different positions like managers, engineers, and support staff. Some roles are much more common, suggesting they are core to the company, while less common roles might require special skills.

•	Employee Age
Most employees are in a specific age group (e.g., 25–35 years), meaning the company has a young workforce. This could reflect the kind of work the company does or its hiring focus.

•	Salary Spending
One team stands out as the most expensive in terms of salaries. This might be because it’s a large team or has many high-paying roles. Certain positions, like senior managers, also cost the most in salaries, showing their importance to the company.

•	Link Between Age and Salary
Older employees often earn more in some roles, likely because of their experience. But in other jobs, age doesn’t seem to impact salary much. This shows that skills and performance might matter more than age.

•	Other Observations
Missing data (like colleges) didn’t affect the main findings but suggests the company could improve its record-keeping.
Charts and graphs made it easy to spot trends and share the insights.

Conclusion
•	This project demonstrates the power of data analysis in uncovering actionable insights from employee data. By completing this project, we gained hands-on experience in data preprocessing, visualization, and storytelling, skills essential for a data analyst role.


