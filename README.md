\# Experiment 1: Data Preprocessing (Data Cleaning) Using Orange



\## Aim

To preprocess the Titanic dataset by handling missing values using Orange Data Mining and generate a cleaned dataset for further analysis.



\## Dataset

\- \*\*Dataset:\*\* Titanic Dataset (`titanic.csv`)

\- \*\*Total Records:\*\* 891

\- \*\*Features Used:\*\* 8

\- \*\*Tool:\*\* Orange Data Mining



\## Workflow

```

File → Impute → Data Table

```



\## Procedure

1\. Loaded the \*\*Titanic\*\* dataset into Orange using the \*\*File\*\* widget.

2\. Connected the dataset to the \*\*Impute\*\* widget to handle missing values.

3\. Applied the \*\*Average\*\* method for numerical attributes and the \*\*Most Frequent\*\* method for categorical attributes.

4\. Sent the processed dataset to the \*\*Data Table\*\* widget.

5\. Verified that the missing values were successfully replaced and the cleaned dataset was ready for analysis.



\## Output

\- Missing values in numerical attributes (such as \*\*Age\*\*) were filled using the \*\*mean\*\* value.

\- Missing categorical values were replaced using the \*\*most frequently occurring\*\* category.

\- The cleaned dataset contained \*\*891 records\*\* with no unresolved missing values in the selected attributes.



\## Observation

The preprocessing step improved the quality of the dataset by removing incomplete entries through imputation, ensuring consistency before performing machine learning or data mining tasks.



\## Result

The Titanic dataset was successfully preprocessed using the \*\*Impute\*\* widget in Orange Data Mining. Missing values were handled effectively, and the cleaned dataset was generated for subsequent analysis.

