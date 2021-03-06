Written with Python 3.5.2

# FDIC-Bank-Data-Organizer
<i>Data Downloaded from</i>: https://www5.fdic.gov/sdi/download_large_list_outside.asp
Make sure to unzip the files into their own folders before kicking off the main script.

<b>Data Sheet Elements</b>
Can be customized to return encoded items as actually readable labels. This data was composed from the readme's included with each download dump. Any number of label lists can be included as long as you follow the pattern.

Main takes 4 dir locations
       <br> 1. Takes Directory where All_Reports for multiple quarters are.
       <br> 2. Takes data_sheet_items_dir
       <br> 3. Takes Excel file name with dir
       <br> 4. Takes location where Condensed/Compiled CSV files will be stored. (Needs to be empty for first run)

Example Output of Python Script:
>main("C:/Users/wyatt/Desktop/FDIC-Bank-Data-Organizer-master/All_Reports/",\
<br>       "C:/Users/wyatt/Desktop/FDIC-Bank-Data-Organizer-master/data_sheet_items/",\
<br>        "C:/Users/wyatt/Desktop/FDIC-Bank-Data-Organizer-master/Compiled_Data.xlsx",\
<br>        "C:/Users/wyatt/Desktop/FDIC-Bank-Data-Organizer-master/Compiled_Files/")
<br>>        Loading data from date: 20180630
<br>>        Loading data for _Assets and Liabilities
<br>>        Loading data for _Income and Expense
<br>>        Loading data for _Net charge-offs to loans
<br>>        Loading data for _Net Loans and Leases
<br>>        Loading data for _Noncurrent loans to loans
<br>>        Loading data for _Performance and Condition Ratios
<br>>        rbc1rwaj not found in _Performance and Condition Ratios
<br>>        Loading data from date: 20181231
<br>>        Loading data for _Assets and Liabilities
<br>>        Loading data for _Income and Expense
<br>>        Loading data for _Net charge-offs to loans
<br>>        Loading data for _Net Loans and Leases
<br>>        Loading data for _Noncurrent loans to loans
<br>>        Loading data for _Performance and Condition Ratios
<br>>        rbc1rwaj not found in _Performance and Condition Ratios
<br>>        Loading data from date: 20190331
<br>>        Loading data for _Assets and Liabilities
<br>>        Loading data for _Income and Expense
<br>>        Loading data for _Net charge-offs to loans
<br>>        Loading data for _Net Loans and Leases
<br>>        Loading data for _Noncurrent loans to loans
<br>>        Loading data for _Performance and Condition Ratios
<br>>        rbc1rwaj not found in _Performance and Condition Ratios
<br>>        Loading data from date: 20190630
<br>>        Loading data for _Assets and Liabilities
<br>>        Loading data for _Income and Expense
<br>>        Loading data for _Net charge-offs to loans
<br>>        Loading data for _Net Loans and Leases
<br>>        Loading data for _Noncurrent loans to loans
<br>>        Loading data for _Performance and Condition Ratios
<br>>        rbc1rwaj not found in _Performance and Condition Ratios
<br>>        Loading data from date: 20190930
<br>>        Loading data for _Assets and Liabilities
<br>>        Loading data for _Income and Expense
<br>>        Loading data for _Net charge-offs to loans
<br>>        Loading data for _Net Loans and Leases
<br>>        Loading data for _Noncurrent loans to loans
<br>>        Loading data for _Performance and Condition Ratios
<br>>        rbc1rwaj not found in _Performance and Condition Ratios
<br>>        Loading data from date: 20191231
<br>>        Loading data for _Assets and Liabilities
<br>>        Loading data for _Income and Expense
<br>>        Loading data for _Net charge-offs to loans
<br>>        Loading data for _Net Loans and Leases
<br>>        Loading data for _Noncurrent loans to loans
<br>>        Loading data for _Performance and Condition Ratios
<br>>        rbc1rwaj not found in _Performance and Condition Ratios
<br>>        Loading data from date: 20200331
<br>>        Loading data for _Assets and Liabilities
<br>>        Loading data for _Income and Expense
<br>>        Loading data for _Net charge-offs to loans
<br>>        Loading data for _Net Loans and Leases
<br>>        Loading data for _Noncurrent loans to loans
<br>>        Loading data for _Performance and Condition Ratios
<br>>        rbc1rwaj not found in _Performance and Condition Ratios
<br>>        Working on importing data to excel for 20180630.csv
<br>>        Working on importing data to excel for 20181231.csv
<br>>        Working on importing data to excel for 20190331.csv
<br>>        Working on importing data to excel for 20190630.csv
<br>>        Working on importing data to excel for 20190930.csv
<br>>        Working on importing data to excel for 20191231.csv
<br>>        Working on importing data to excel for 20200331.csv
<br>>        Working on Populating Dashboard Data Lookup

End Goal for this project is to provide easily accessible insights into: 
  Individual bank health over time
  Total systematic risk within the US markets
