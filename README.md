Please change the lines of XVG input. The code gives you X or Y axis for easy import into excel.

If you want to directly convert to excel, use the second script.

Prerequisites: Pandas could be installed via pip:
pip install pandas openpyxl

How it works:
Read .xvg file: The script reads the specified .xvg file and extracts X and Y values into lists.
Display columns: As before, you can choose to display either the X or Y column, and the output is cleared before showing the selected column.
Save to Excel: When you type save, the program will ask for an Excel file name (e.g., output.xlsx) and save the X and Y columns into an Excel sheet.
Pandas: The pandas library is used to convert the X and Y lists into a DataFrame and then export it to Excel format.

