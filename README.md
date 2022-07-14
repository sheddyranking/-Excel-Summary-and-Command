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

> Result Worksheet =>: https://github.com/sheddyranking/-Excel-Summary-and-Command/blob/main/Sort%20and%20filter%20-%20Copy.xlsx


### VLOOKUP, HLOOKUP, LOOKUP, iNDEX_MATCH.

#### VLOOKUP
> looks for a value in the leftmost column of a table and then return a value in the same row of the column you specofy.

> `Left-Most`, This means which ever column your looking for a value in it most be `Left-most`, to archive this you most define a new `Table Name` to reference to when including it in the range. 

##### has the Following attributes

> 1. `LookUp value` - The Value to be Found in the First Column of the Table.

> 2. `Table_Array` - The Table which the Data is being Retrieved From, this can be the original table if the value is from the first column or a New `Table Name` range.

> 3. `Col_index_Num` - The Column Number from the Table_array which the Matching Value Should be Retrived from. NB. the first column in the Table_arrya is 1.

#### HLOOKUP

> This is same with `VLOOKUP`, the only only is, it search for a value horizontally from left to right. `Col-index-Num` Most be the top-left most.


#### LOOKUP

> This can be done with `VLOOKUP` and `HLOOKUP`, But instead to save more time, `Lookup`, only include the `Col-index_Num` from the Column in which the data is to be Filtered.


#### INDEX MATCH FUNCTION

> The Index Match Function can be used to Filter out a value as well.

> Look at his example `INDEX(A1:F30,MATCH(B2,C1:C30,0)6)`

> `A1:F30` - This represents the `Table Index-range`.

> `B2` - The `Match Value`, the Value to be searched in the Table index-range.

> `C1:C30` - This represents the `Col-index-num`, where the Match Value is located 

> `0` - This represent `FALSE` which means the match value, must be `Exactly`.

> `6` - The column index num of the Match value `result ouput`. 

> NB: There are instances where the column index number of the match value can also be Match. eg.`INDEX(A1:A21,MATCH(J12,E1:E21,0),MATCH(A1,A1:A21,0))` (Here, we selected only the column where the match value can be found and still meatch it 0n the same column)

### Data Analysis

> Data analysis in Excel can be done with `Excel add-ins`, navigate to `File > option > add-ins > go > check(data analysis & solver)` 

> After, Nagivate to `Data > left-most side` to access `Data analysis` or `solver` to perform analysis. 



