# Experiment 1: Data Cleaning and Preprocessing Using Orange

## Objective

To prepare the Titanic dataset for analysis by identifying and handling missing values using Orange Data Mining.

## Dataset Details

- **Dataset Name:** `titanic.csv`
- **Total Instances:** 891
- **Number of Features:** 8
- **Software Used:** Orange Data Mining

## Workflow

```text
File → Impute → Data Table
```

## Steps Performed

1. Imported the **Titanic** dataset into Orange through the **File** widget.
2. Connected the dataset to the **Impute** widget for missing value treatment.
3. Configured the imputation method by assigning:
   - **Mean** for numerical attributes.
   - **Most Frequent** for categorical attributes.
4. Linked the processed output to the **Data Table** widget.
5. Examined the resulting dataset to ensure all missing entries were appropriately handled.

## Output

- Missing values in the **Age** column were replaced with the corresponding mean value.
- Missing categorical attributes were filled using the most commonly occurring category.
- The processed dataset retained all **891 records** while improving data completeness.

## Discussion

Applying imputation removed incomplete data issues without discarding records. This preprocessing step enhanced the reliability and consistency of the dataset, making it suitable for visualization, statistical analysis, and machine learning tasks.

## Conclusion

The Titanic dataset was successfully cleaned using the **Impute** widget in Orange Data Mining. The resulting dataset is complete, consistent, and ready for further data mining and predictive analysis.
