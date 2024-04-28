# HR-Analytics-Statistics-
Executed a rigorous data refinement process, culminating in a comprehensive statistical analysis. Applied advanced statistical methodologies, including hypothesis testing, one-sample z-test, one-sample t-test, two-sample t-test, and  F-test, to glean nuanced insights amidst a dearth of correlation

### Dataset Description
## Detailed Overview of the HR Analytics Statistics Jupyter Notebook

### Dataset Description
The provided Jupyter notebook analyzes a dataset containing information about 14,999 employees. The dataset includes the following columns:

1. **satisfactoryLevel**: The satisfaction level of the employee, ranging from 0 to 1.
2. **lastEvaluation**: The score of the employee's last evaluation, ranging from 0 to 1.
3. **numberOfProjects**: The number of projects the employee has worked on.
4. **avgMonthlyHours**: The average number of hours the employee works per month.
5. **timeSpent_company**: The number of years the employee has been with the company, ranging from 2 to 6 years.
6. **workAccident**: Whether the employee has had a work accident (0 = no, 1 = yes).
7. **left**: Whether the employee left the company (0 = no, 1 = yes).
8. **promotionInLast5years**: Whether the employee received a promotion in the last 5 years (0 = no, 1 = yes).
9. **dept**: The department the employee works in.
10. **salary**: The salary level of the employee (low, medium, or high).

### Key Steps and Findings
1. **Data Cleaning and Preparation**:
   - The dataset initially had a column naming issue corrected using `df.rename()`.
   - Duplicates were identified and removed, reducing the dataset to 11,991 rows.
   - No missing values were found in the dataset.

2. **Descriptive Statistics**:
   - Descriptive statistics were calculated for the dataset, providing insights into the distribution and summary of numerical attributes.
   - The mean satisfaction level was approximately 0.63, with a standard deviation of 0.24.

3. **Data Visualization**:
   - A histogram was plotted to visualize the distribution of the satisfaction level attribute.
   - A density plot was created to show the density of the satisfaction level attribute.

### Key Findings
1. The dataset has 14,999 rows and 10 columns, with no missing values.
2. The `timeSpent_company` column indicates the number of years an employee has been with the company, with values ranging from 2 to 6 years.
3. The `left` column indicates whether an employee left the company (1) or not (0).
4. Preliminary analysis suggests that employees with lower satisfaction levels, fewer projects, and lower monthly hours are more likely to leave the company.

### Algorithms and Analysis
- The notebook includes data exploration, descriptive statistics, and visualizations to understand the employee data better.
- Algorithms like data cleaning, descriptive statistics, and data visualization techniques were applied to gain insights into employee attributes and turnover.

### Usage and Contribution
- The code in the notebook can be used to analyze HR data and understand factors influencing employee turnover.
- Contributions to enhance the analysis, add more algorithms, or improve visualizations are welcome through pull requests or issue submissions.
