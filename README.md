# Stout-Take-Home-Case-Study

Used Python (Pandas) and SQL in a Google Colab Jupyter Notebook to process the customer revenue data and calculate the 10 metrics required for the case study.

## Data Cleaning and Quality Checks

### Data Cleaning
- Removed leading and trailing whitespace from customer email addresses to ensure consistent customer identification. Without this step, identical email addresses with different whitespace could be incorrectly treated as separate customers. It was unclear whether email addresses should be treated as case-sensitive when identifying unique customers. I did not normalize email addresses to lowercase, so email addresses differing only by capitalization may be treated as separate customers. This assumption would need to be clarified to ensure consistent customer identification.

### Data Quality Checks
- Verified that the dataset contains only three years of data, as specified in the project requirements.
- Checked for null values.
- Reviewed `net_revenue` values for potential data quality issues.

## Reproducing Notebook Output

To reproduce the notebook output, upload the notebook and take home dataset to [Google Colab](https://colab.research.google.com/) and run the cells in order.

## Tableau Dashboard

View the interactive Tableau dashboard below (There are two dashboards):

[View Tableau Dashboard](https://public.tableau.com/app/profile/andy.li5977/viz/AndyLiCaseStudyDashboardforStout/CustomerRevenuePerformanceDashboard)
