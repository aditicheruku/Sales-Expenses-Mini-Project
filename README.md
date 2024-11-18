Garv have been given 2 CSV files: one with the sales data of a ice cream store and one with the expenses data. His task is to merge these files based on the days of the week, then update a value in the merged dataframe, remove a column which is not needed any more, handle any missing values, and then get some statistics about the combined data. So how would he write a Python program using pandas to accomplish all these tasks? Can you help him complete this task.



Sales Data: https://drive.google.com/file/d/1H0nx3Kuf7_WGm9QWUlhA2Q1EMceSkqOZ/view?usp=drive_link



Expense Data

https://drive.google.com/file/d/1NsughbtlDRamHr1B-tSh7ro_ruBN3ETR/view?usp=drive_link



﻿

HINT:

To get you started, here's a step-by-step plan:

Read the data from 'Data of sales.csv' and 'Data of expenses.csv' into two separate DataFrames.
Merge these DataFrames based on the 'Days' column.
Update the 'Cups Sold' value for Wednesday from 50 to 55.
Remove the 'Cups Sold' column from the merged DataFrame.
Check for missing values and fill all missing values with 0.
Get a statistical summary of the data and display information about the DataFrame.
Print the final DataFrame.
