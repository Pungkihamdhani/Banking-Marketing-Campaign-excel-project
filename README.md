**Banking Marketing Campaign Project Overview**

In this project I'll be working on "Banking Marketing Campaign" dataset, it tells us about the number of conversions from a program campaign offered through communication channel conducted by Bank

For data analysis process, I use excel for data cleaning, preparation, transformation, visualization, statistical analysis and dashboard, and there are several rows that impacted during the process and also some new rows were made to obtain the desired result 

First thing that I notice, that there were no primary key, no row that has unique value on each column, so I create "ID row" to distinct each customer

Next "age row", in this row there are too many values which vary from 18 to 80, so to make it simplier, I create "age range" using IF function, the purpose is to group these values to certain age stages so it be easier for us to do the "by age" analysis process

 
![image](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/add75808-1195-4770-89e8-df99fd2262f8)



I create Pivot table as shown above, a Pivot Table in Excel is a powerful tool used for summarizing, analyzing, exploring, and presenting large sets of data. It allows you to dynamically reorganize and filter your data, providing a flexible and interactive way to look at different perspectives of your data set, below is one of the pivot table that I created

In below pivot table, data are filtered by occupation, populated the value with customer ID and categorized by conversion rows (converted, not converted), the purpose of this table is to **analyze the conversion rate based on occupation**

![image](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/7728eda8-71ab-48a0-a2be-1dd7c6c50b2b)

To get a better understanding of the table above, I add "population share" row (in percentage) by using below formula:

**total customer of each occupation / the grand total customer of all occupation type X 100**

by having these value, we can analyze the population of each occupation role to the whole occupation population, whether these roles has a significant impact to the marketing campaign. I use pie chart to vizualize for an easy view

Next, I create "conversion rate" row of each occupation type, I populated the values by using below formula:

**conversion number of each occupation / total customer of each occupation x 100**

This row shows the effectiveness of the marketing campaign by calculating the conversion rate of each occupation role 

![Conversion rate table](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/db0dc1b3-67df-4f60-9818-e0b7a1905eeb)

the cell highlighted in pink are cells with value that met the criteria

![chart by occ overview](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/2c7b89be-5a5c-418e-b70d-6bfc3a47546c)

![Conversion Rate dashboard](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/4311c469-745b-41f2-a24f-50c49da7613e)

Lastly I add "recommendation" row, this row will inform us which occupation role are recommended as the suitable market segment for the product, I use IF function with parameter / Criteria as follow :
      
      Minimum number of customer from each occupation role are 2,000 customer  
      
      Minimum Conversion Rate of each occupation role are above 10%

So eventhough "Student" has the highest conversion rate, but will not be recommended by the system due to the contribution rate is just 2%, too small to have impacted the whole market,
whilst "Manual worker" has the third highest contribution rate of 21.5%, unfortunately the conversion rate is only 7%, if we decide to work on "manual worker" it will be to **costly and consume too much time**  

![Recomm by occ](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/213188f2-8cdf-4186-b54a-0650f1a8965d)




![By  Comm Channel](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/0c712728-748b-4c58-8778-dd31ca28ffad)
![Previous vs Current](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/49eff9a3-5a25-444e-a1d7-b4379b69550e)
![Growth Previous vs Current](https://github.com/Pungkihamdhani/Banking-Marketing-Campaign-excel-project/assets/167069740/01f89a70-343f-45f0-bc90-ed3c49a95ad0)
