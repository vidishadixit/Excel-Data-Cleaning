# Excel-Data-Cleaning
Data cleaned using Excel with Power Query

# Data downloaded from Kaggle:
https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset/data

# Steps followed:
Historical Sales Data CSV download
Remove duplicates
TRIM() – removes extra spaces
UPPER(), LOWER(), PROPER() – fixes inconsistent text
LEFT(), MID(), RIGHT() – helps extract exactly what you need
SUBSTITUTE() – replaces unwanted values
CLEAN()- clean non-printed junk data
Change to appropriate data types
The ratings column has a non-numeric value - In Power query, replaced the | to 1
"User_id and User_name have comma-separated values-
-split using delimiter
-add index column from 0
-unpivot the splitted columns
-This has attribute and value columns
-split attribute column by ""."" delimiter and rename attribute type and user index
-pivot attribute type using value column and don't aggregate
-columns will be segregated accordingly
-delete unwanted columns and the data is ready."
Separate categories columns
