# Excel-Data-Cleaning
Data cleaned using Excel with Power Query

# Data downloaded from Kaggle:
https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset/data

# Steps followed:
1. Historical Sales Data CSV download
2. Remove duplicates
3. TRIM() – removes extra spaces
4. UPPER(), LOWER(), PROPER() – fixes inconsistent text
5. LEFT(), MID(), RIGHT() – helps extract exactly what you need
6. SUBSTITUTE() – replaces unwanted values
7. CLEAN()- clean non-printed junk data
8. Change to appropriate data types
9. The ratings column has a non-numeric value - In Power query, replaced the | to 1
10. "User_id and User_name have comma-separated values-
-split using delimiter
-add index column from 0
-unpivot the splitted columns
-This has attribute and value columns
-split attribute column by ""."" delimiter and rename attribute type and user index
-pivot attribute type using value column and don't aggregate
-columns will be segregated accordingly
-delete unwanted columns, and the data is ready."
11. Separate categories columns
