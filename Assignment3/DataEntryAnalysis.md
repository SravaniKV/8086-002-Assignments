# DateEntryAnalysis.md:
This document is related to assignment3 and contains Issues and possible resolutions for the files provided.
# List of files provided:
[Pond2010](https://github.com/SravaniKV/8086-002-Assignments/blob/master/Assignment3/pond2010.xlsx)  
[zooptemp](https://github.com/SravaniKV/8086-002-Assignments/blob/master/Assignment3/zoop%20-%20temp.xlsx)  
[zoomtemp-main](https://github.com/SravaniKV/8086-002-Assignments/blob/master/Assignment3/zoop%20-%20temp-main.xlsx)

# Description:
In this assignmnet we were provided with the datasets(3 files) providing the study of 2 species of zooplankton across multiple years.
The type of zooplankton they studied is called rotifers generally, and specifically the genus Conochilus, in which groups of individual
rotifers stick together in colonies. The investigators plan to repeat this study for several more years.

# Task 1 -Issues identified:
1.  In zoop -temp.xlsx file which shows the data from station B has the comment line "Station B is in a shallower southern arm of the lake,see yellow notebook for map and details".But, there is no yellow notbook for map and details.  
2. The units of measurements of the columns in the files are not provided.Example temperature not sure if it is C/F.
3. There is no details about the time at which the data was collected. There are only details of the date on which they were collected and so it is not possible to investigate on day and night distribution samples of specimen which was mentioned in the assignment scenario.
4. Not all columns are defined. For example in the file Pond2010.xlsx there is a column name 'z' , but no info was provided about that.
5. Some of the data in files are -ve values like, in the file zoop- temp.xlsx there are cells with -ve values in the column Chippo #/L.
6. Some of the rows in the file are in different colour like red/orange, but no information was given why they were different from other rows.
7. The graphs provided in the files doesnt have the y-axis and x-axis defined. But when we click on the graph, the corresponidng columns are getting highlighted in the excel. The axis needs to be defined.
8. The column definitions are abbreviated  and they are not explained anywhere, So it leads to multiple assumptions and mis interpretations of the data.
9. The pond2010.xlsx contains the data of 2010 where as the other files has the data collected in 2011, though the study was conducted over several years, i think there should be some additional information provided in order to integrate the different years file and make the analysis.
10. The files are having the similar column data so they can also be combined into same file.
11. There are formulas for some cells in the excels but not for all others. For example zoo-temp main.xlsx has formulas for chippo#/L column of data colleted on 6/7/11 and not for 6/4/11. Needs some more info on this for better analysis.

# Task2 - Solutions for the Issues identified in Task 1
Suggest a new system for organization. Create a table in your Markdown document showing a potential template for later years of data collection that would address the problems you identified in #task1. 

1. Provide the information on yellow notes and also the links for the maps and details.
2. Units of measurements for the columns can  be included along with the column names in the excel files.
3. There can be additional column with sample collection time details along with the date details.
4. There can be an additional sheet or clear naming of the columns can be done in the same excel. Which gives better meaning of the columns and the collected data.
5. The -ve values can be rectifiled/rechecked in the excel and needs to be given a thought if the column can really have -ve values.
6. There should be clear details provided for the rows that are in different colours to make the maximum usage of data and to proceed with  analysis.
7. The x and y axis should be given proper naming in order to get the quick and easy information from the files.
8. Proper naming of the columns is necessary inorder to reduce confusions.
9. There should be a column/sheet for additional information provided as the data collected was in different years and this could help in corelating the files and heps in analyzing.
10. The data in the files can be combined and placed in same excel and an additional column can be added showing the different station names.
11. The formulas for the cells needs to be consistent or needs to be explained or provided info in the excels.


## Below can be the format of the excel:

| Date | Time(EST) | Temperature (Celsius/Fahrenheit) | Density (liters) | Colony Diameter(meters) | Species | ColonyDiameter (meters) | Depth (millimeters) | Cuni #/L | Cuni ColonySize (meters) | Chippo #/L | Chippo ColonySize (meters) | Chla | Station  (location) | Additional Information |
|------|-----------|-------------------|------------------|-------------------------|---------|-------------------------|----------------|----------|--------------------------|------------|----------------------------|------|---------------------|------------------------|






