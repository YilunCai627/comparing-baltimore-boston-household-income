# Comparing the Household Income in Baltimore and Boston
## Background
 Household income statistics is instructive when comparing economic well-being and living standards between different cities. With the steady development of the US economy, however, racial household income inequality remains a challenging social issue. Household income levels vary across different race in the United States.  

  ***How is the overall economic performance different from cities? To what extent is the economic inequalities by race? We'll compare the household income by race in Boston and Baltimore and further explore the racial income gap and population diversity with open data from the Opportunity Insights team’s [Opportunity Atlas](https://www.opportunityatlas.org).***

## Data Insights

### **1. Differences in Overall Economic Performances** 

Here is the comparison of overall economic performances in Boston and Baltimore based on basic statistics of household income:  

![](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/raw/master/Charts/Income_CitiesComparison.png)  

From the basic calculation of household income statistics in both cities, we can have a sketch of the entire economic conditions. Basically, Boston performs better as regards to various measurements related to household income.


### **2. How about Population Diversity？**

The chart below helps facilitate clear comparisons of the population diversity between Boston and Baltimore based on the amount of valid data at the census tract level.   

![](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/raw/master/Charts/Population%20Diversities.png)

Boston has a strong mix of people from several different racial backgrounds, while the racial composition of Baltimore is more concentrated. In fact, according to [new Census data](https://www.bostonindicators.org/article-pages/2018/september/boston-diversity) released in 2018, Boston is now the sixth most diverse U.S. city.  

### **Detour: Python Data Visualizations**
Python is a widely available and open source computer programming languages to conduct similar data analyses as Microsoft Excel. We'll work with the integrated data in Excel Document and implement statistics calculation and data visualization using Python. The [**Python notebook (.ipynb) files**](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/blob/master/pie%20chart_ppl%20diversity.ipynb) in this repository contains the process of data manipulation. The figure below display the pie chart generated in python using the [*matplotlib*](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.pie.html) module.  

![](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/raw/master/Population%20Diversity%20of%20two%20cities_plt.png)


### **3. Similarities in Racial Income Gap**

Having racial diversity, however, is far from enough to guarantee that opportunity is equal. Below charts display the racial wealth divide in Boston and Baltimore based on levels of household income determined by percentile of average income in each city obtained from [Opportunity Atlas](https://www.opportunityatlas.org):  

![](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/raw/master/Charts/Racial%20Wealth%20Divide_BOS.png)

![](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/raw/master/Charts/Racial%20Wealth%20Divide_BAL.png)  

Through the above results, we have a clearer understanding for the challenges of racial economic inequality in both cites. This racial income gap is most pronounced between white households and racial minorities. Interestingly, the very small Asian community has been on a par with or has even exceeded white income based on limited available data. **Therefore, it is necessary to identify better practices and policies that can address the economic inequality and the racial wealth divide in different US cities.**

## Data Analysis
Want to learn more details about data manipulation in Excel to analyze and visualize the result? Click [***here***](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/blob/master/Data%20Manipulation.md) for a simple **step-by-step instructions**!

## Data Sources  
1. [Household Income by Census Tract, Race in Baltimore](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/tree/master/original%20data/BALTIMORE)
2. [Household Income by Census Tract, Race in Boston](https://github.com/YilunCai627/comparing-baltimore-boston-household-income/tree/master/original%20data/BOSTON)
3. [Codebook for variable description](https://opportunityinsights.org/wp-content/uploads/2019/07/Codebook-for-Table-4.pdf)
4. [Opportunity Atlas](https://www.opportunityatlas.org)