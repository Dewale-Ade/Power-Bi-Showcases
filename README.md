    Dataset  source

The original data file is from:
https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx

    Taking notes while transform data into Power BI before visualizations:

1. Loaded file and clicked "Transform Data".

2. I deleted empty columns.

3. For column Q1, I right clicked > Splited Column by Delimeter > --Custom-- > ' (specified)' > Split. Removeed the second splitted out column.

4. For column Q5, I right clicked > Splited Column by Delimeter > Colon, delete the right splitted column.

5. For column Q3, I made a duplicate column for below steps.
   Split Column > By Digit to Non-digit, delete the 3rd column with all 'k' values.
   For the 2nd column, use 'replace value' to remove '-', 'k' and '+' (to the maximum number 225).
   (Menu)Add Column > Custom Column > New column name > 'Average Salary', wrote query to calculate from Q3.Copy1 and Q3.Copy2 to calculate.
   Moved the 'Average Salary' by Q3 column.

6. For column Q11 abd Q4, I did the same as for column Q1.

