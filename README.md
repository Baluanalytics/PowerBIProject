# PowerBIProject
Project Title: Investment Analytics

Problem Statement:

Investment is a game of understanding historic data of investment objects under different events but it is still a 
game of chances to minimize the risk we apply analytics to find the equilibrium investment. To understand the Foreign direct investment in 
India for the last 17 years from 2000-01 to 2016-17. This dataset contains sector and 
financial year-wise data of FDI in India Sector-wise investment analysis and Year-wise investment analysis

Tools used
	Power BI 
	Power query Editor
	Excel for dataset

Minimize the number of fields  
The given data set contains only the required number of fields. So, there is no need to remove any fields. 

Minimize the number of records
	I could utilize all records of the dataset because it contained records that are valid and ready for consumption	

Optimize extracts to speed up future queries by materializing calculations, removing columns and the use of accelerated views   

1.	The first row in the CSV file is a header. So, before using the dataset for processing in the BI, I configured the first row as the header in power query editor.
2.	Every column data type has been changed to Decimal except first column which is in text data type.
3.	Added a new column to represent the sum of every column in the row from 2001-01 to 2016-17 and also renamed column name as Total-2001-2017.
4.	Added a new column to show the minimum amount of all columns in a given row from 2001-01 to 2016-17 in all Sectors and also renamed column name as Minimum.
5.	Added a new column to show the maximum amount of all columns in a given row from 2001-01 to 2016-17 in all Sectors and also renamed column name as Maximum.
6.	Added a new column to show the average amount of all columns in a given row from 2001-01 to 2016-17 in all Sectors and also renamed column name as Average.
7.	In Power Query Editor Ribbon View menu bar, under column quality, column distribution and column profile have been checked for correctness
8.	As a final step, closed and applied then loaded data into Power BI Report.

