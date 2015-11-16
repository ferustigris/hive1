# hive1
1.	Store dataset http://stat-computing.org/dataexpo/2009/the-data.html (year 2007 + dimensions http://stat-computing.org/dataexpo/2009/supplemental-data.html only Airports and Carrier Codes) on HDFS and expose it through Hive 
2.	Count total number of flights per carrier in 2007
3.	The total number of flights served in Jun 2007 by NYC (all airports, use join with Airports data). How many MR jobs where instanced for this query?
4.	Find five most busy airports in US during Jun 01 - Aug 31. How many MR jobs where instanced for this query?
5.	Find the carrier who served the biggest number of flights

The datasets (as CSV files) should be loaded to Appropriate places into HDFS before script is started
