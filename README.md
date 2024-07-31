# Power-BI-analysis-by-faria

This project involves cleaning and analyzing expense data using Power BI. Below are the key steps undertaken:

1. **Import Data and Open Power Query**
    - Imported the dataset and opened it in Power Query for data cleaning and transformation.

2. **Correct Spelling and Punctuation Errors**
    - Fixed errors in the `Expense Type` column for consistency.

3. **Standardize Project Names**
    - Ensured uniformity in project names across the dataset.

4. **Handle Missing Currency Values**
    - Created a new column to handle missing values in the `Currency` column based on the `Amount`.

5. **Normalize Amount Column**
    - Converted all amounts to INR based on the `Currency` column.

6. **Calculate Total Reimbursed Amount in INR**
    - Created a measure to calculate the total reimbursed amount in INR.

7. **Calculate Total Reimbursed Amount for Project_B**
    - Used a measure to determine the total reimbursed amount specifically for `Project_B`.

8. **Count of Declined Requests**
    - Created a measure to count the number of declined reimbursement requests.

9. **Visualizations**
    - **Slicer Visual**: Added slicers for `Project` and `Employee`.
    - **Column Chart**: Visualized reimbursement amounts for each employee.
    - **Pie Chart**: Showed the distribution of reimbursement amounts across different projects.

## Conclusion

The dataset was successfully cleaned and transformed, enabling meaningful analysis and visualization of expense data. Key metrics were calculated, and insightful visualizations were created to facilitate better understanding.
