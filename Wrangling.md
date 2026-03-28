## Data Wrangling Process 
The datasets used in this project were obtained in raw CSV format and required cleaning and preparation before analysis. Several steps were taken to ensure the data was accurate, consistent, and suitable for exploratory analysis.

## Handling Missing Values 
Missing values were assessed across all datasets. Where missing values were minimal and did not significantly affect the dataset, the corresponding rows were removed to maintain data quality. In cases where missing values appeared in non-critical fields, they were retained or flagged, as imputing values could introduce bias and reduce the reliability of the analysis.

## Removing Duplicates 
The datasets were checked for duplicate entries, and any exact duplicate rows were removed to ensure that each observation represented a unique data point. This step was particularly important for maintaining accuracy in variables such as job vacancies, labour force participation, and unemployment rates.

## Standardizing Formats 
Formats were standardized across all datasets to ensure consistency. Date variables were converted into a uniform format, such as year or year-month, to allow for alignment across datasets. Column names were cleaned to remove inconsistencies, and numerical values were formatted appropriately to ensure they could be analyzed without errors. Additionally, categorical variables, such as education levels, were standardized to avoid inconsistencies in labeling.

## Filtering Unnecessary Data 
Unnecessary data was filtered out to focus the analysis specifically on Ontario’s labour market. Rows containing data from other regions were removed, and columns that were not relevant to the decision problem were excluded. This step helped reduce noise and ensured that the analysis remained focused and interpretable.

## Joining Multiple Datasets 
To enable comparisons across variables, multiple datasets were joined using common fields, primarily time-based variables such as year. For example, job vacancy data was aligned with unemployment data to analyze the relationship between labour demand and labour supply, while labour force participation data was used alongside unemployment trends to provide additional context.

## Aggregating Data
In some cases, data was aggregated to a higher level to improve clarity and consistency. More granular data was summarized into yearly averages to simplify analysis and ensure alignment across datasets with different time intervals. This allowed for clearer visualization of trends and patterns.

## Pivoting and Reshaping
Certain datasets were reshaped to support analysis and visualization. Data was reorganized where necessary to allow for comparisons across categories, such as education levels, and to ensure compatibility with visualization tools. This restructuring made it easier to generate meaningful charts and identify key insights.

## Summary 
Overall, the data wrangling process focused on improving data quality, consistency, and usability while preserving the integrity of the original datasets. These steps ensured that the subsequent analysis accurately reflects labour market dynamics and supports informed decision-making.

