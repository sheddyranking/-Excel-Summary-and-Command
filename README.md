# -Excel-Summary-and-Command
Excel Summary and Command for Data Analystics


## Excel Summary and Command 

### ADD

> =SUM (addition), or use the command `Alt + =` to add values. 

> =SUMIF(A1:A10,"<>50") = This Sums a Column or row with Conditional statements (<>, <=, => <, >)

### Fill

> Right Click and drag to Auto fill Fomular, or Highlight the Column and Enter `Ctrl+D` to fill down and Highlight Row Enter `Ctrl+R` to fill right.  

### Split 

#####  Spliting Data Stuff into one Column

> `Click Home > Fill > Flash Fill`. or Enter Command `Ctrl+E`

#####  Split a column based on delimiters.

1. > Click and drag to select the cells from top to bottom. 
1. > On the `Data` tab, click `Text to Columns`. Make sure that `Delimited` is selected, and then click `Next`.

2. > Under `Delimiters`, make sure that `Comma `is the only checkbox selected, and then click `Next`.

3. > Click the `General` option. 

4. > Finally, click inside the `Destination` box and type  starting Address e.g`$D$32`. Then click `Finish`.


### Transpose
When you need to rotate columns and rows, you transpose them in Excel.

##### Switch data around by transposing it

1. >  Click and drag to select the cells to be transposed.

2. > Now you'll copy the cells.

3. > On the `Home tab`, click the arrow under the `Paste` button.

4. > Click `Paste Special`, and then at the bottom, click the checkbox for `Transpose`. Click `OK`

5. > Alternatively, you can Enter Commnd `CTRL+ALT+V`. 

##### Transpose using Formular.

1. >  Cell the blank cells equal wiht the one conatianing Data.

2. >  Enter formular `Transpose(table data Address)`  don't hit enter yet.

3. > press `Ctrl+Shift+Enter`

4. >  the table should be populated with transpose data.

### Sort and Filter

> Hihglight the Table `Ctrl+A` and goto `Home>sort&filter>Filter` to apply filter on the table.

> Similary you can click on a single cell and apply the desired filter you choose to perform.


### Tables 

> `Ctrl + T` for comverting a data to a table. 

> You can Enter `=SUM` on a row tables to get the total sum.

>  `Alt` + `=`  to get the total Column summation, or from `Table Design>Total Rows` to get the column summation, there's a Filter Button that allows you to change it to averagr, Max, Min etc.

### Analyze

> click on any cell and enter command `Ctrl`+`Q` and click on the drop down panel, you can select a `data bar`, `chart`, `totals` or `sparklines` for trends. 


### Chart

> you can click on a table cell goto `insert>Recommended Chart` and choose a chart that best represents your visuals.

>  Also you can click on the chart goto `Chart Design > Add chart Element` and add other details like `Trendlines` etc.


### PivotTable.

> Click on any cell on a table data and goto `Insert>PivotTable>Existing Worksheet` and Enter the Address of the Table from the starting Column.

> The PivotTable Panel will appear, you can go and summaries the worksheet.



## Sorting and Filtering Question and Answer Result Excercise on Housing Data.

> Q1. Sort the data in newest to oldest order of date listed.

> Q2. Sort the data in ascending order of Area and descending order of Agent name

> Q3. Sort the data according to the following order of Area - S. County, Central, N. County.

> Q4. Find all the houses in the central area.

> Q5. Find the list of all the houses in the central region with Pool and S. County without Pool.

> Q6. The agents with a house in N Country area having 2 bedrooms and a single type family.

> Q7. Display all the houses whose list price was between 300000 to 400000

> Q8. Find all the houses in the N. Country area with a list price > 300000 and having 3 or 4 bedrooms.

> Result Worksheet =>: 


