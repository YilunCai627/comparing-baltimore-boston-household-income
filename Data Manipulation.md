## Step-by-step descriptions on data manipulaion and results visualization in Excel
### 1. Download the original data and change data format
* Download data containing Household Income of different races within Baltimore and Boston repectively.  

* Change the data format from .csv to .xlsx. 

### 2. Apply VLOOKUP and AutoFilter to integrate data within a city in different files
* Apply **Data >> Autofilter** to filter and remove data beyond the specified city in each file.  

* Integrate the data of household income for different races within a city using **VLOOKUP** function based on the unique tract code. 
 

### 3. Basic statistics for each city using build-in functions
* Calculate the **MIN/MAX/AVERAGE/MEDIAN** of household income using Excel's build-in functions to have a overview of the differences between cities.  

* **COUNT** the number of available data for different races to compare the ethnic diversity.

### 4. Apply IF statement and AutoFilter to reorganize the household income level  
* Determine the income levels for different cities based on the percentile income data of Opportunity Data. More specifically, the value of household income less than 33th percentile as "low", between 33th percentile and 66th percentile as "middle" and greater than 66th percentile as "high".  

* Use **IF statement** in Excel to filter the level of household income and reorganize the data by assigning labels of different income levels.  

### 5. Generate chart in different types for results visualization.  
* To compare the overall household income between different cities, insert **Clustered Bar Chart** to show the similarities and differences.

* To compare the racial wealth divide in each city, insert **Stacked Column Chart** to display the household income level by race.

* To compare the ethinic diversity between different cities, insert **Pie Chart** to visualize the distribution of different races.
