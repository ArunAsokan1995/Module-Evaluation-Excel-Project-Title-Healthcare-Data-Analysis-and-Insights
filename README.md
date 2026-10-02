# Module-Evaluation-Excel-Project-Title-Healthcare-Data-Analysis-and-Insights
## Hospitalisation Details
1.  Check for the number of missing values marked with '?' in each column. Using COUNTIF(A:A,"?") formula, found the count of '?' in each column
2.  Fill in the missing values of ‘month’ with Sep. Replaced ~? With "Sep" using Replace option.
3.  Found average of year, Round of Average and Filled 1983 for columns with "?".
4.  Determine the most frequently occurring values in the 'Hospital tier' with help of pivot and replaced ~? With "tier - 2" using Replace option.
5.  Determine the most frequently occurring values in the 'Hospital tier' with help of pivot and replaced ~? With "tier - 2" using Replace option
6.  State ID' values are missing, filled with most frequent State Code with help of pivot and most frequent is R1013, Replaced ~? With "R1013" using Replace option
7.  Merged ‘year’, ‘month’ and ‘date’ columns in the “Hospitalization Details” Table into one column named ‘Date of Birth’ and format it in ‘DD-MMM-YYYY’ custom format. Equation used CONCATENATE(D2&"-"&C2&"-"&B2)
8.  Age Calculated. Equation used DATEDIF(E2,DATE(2023,6,8),"Y")
9.  Format of ‘charges’ column changed to currency ($) from formats - currency types
## Medical Examinations
1.  Check for the number of missing values marked with '?' in each column. Using COUNTIF(A:A,"?") formula, found the count of '?' in each column.
2.  Determine the most frequently occurring values in the ‘smoker’, Basis to pivot table, most of the persons are non smokers. Hence, the "?" has replace with "No".
3.  Convert the "Number Of Major Surgeries" column in the “Medical Examinations” Table to numerical data. Replaced No major surgery with "0" using Replace option.
4.  No inconsistencies found in between 'Heart Issues' and 'smoker' columns
5.  Created a new column named “Weight Status” basis to BMI Categorisation. Equation used "IF(B2<18.5,""Underweight"",IF(B2<25,""Normal Weight" "IF(B2<30,""Overweight"",""Obesity"")))".
6.  Created a new column named “Diabetes Status” basis to HbA1C Categorisation. Equation used "IF(C2<5.7,""Normal"",IF(C2<6.5,""Prediabetes"",""Diabetes""))".
## Customer Names
1.  Splited the Name into 2, using text to column with comma separated.
2.  Again, Splited the 2nd name using text to column with fixed length delimiting.
3.  Post removed unwanted comma, dots and cleaned/trimmed all the names and arranged in order.
## Healthcare
1.  One New table created.
2.  Merged all details with VLOOKUP function. Equation used   VLOOKUP($A2,'Medical Examinations'!$A:$J,2,FALSE)
3.  Trimmed, cleaned and made all things in proper manner.
## Pivots
Based on the new table created 6 pivot tables and created pivot charts based on the requirements.
## Dashboard
1. Copied the Pivot tables and charts to the new dashboard sheet.
2. Arranged the data.
3. Insert the slicers and connected between other tables.
