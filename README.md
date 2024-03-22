# Bird-Strike-Analysis

## INTRODUCTION
In this project I analyzed bird strike incidents by different airlines and found the top 10 airlines with greatest incidents. Moreover, I also analyzed the number of bird strike incidents based on month and year and created a bar chart visualization using RDBMS, and Amazon RDS as my SQL server.

## PROJECT DESCRIPTION
The data that I sued in this project was 6MB, with almost 25,500 rows and 19 columns (Rid, Aircraft, Airport, model, wildlife_struck, Impact, ect.,). First I loaded my data into my SQL server (Amazon RDS) and accessed it using RDBMS (You can also perform the same analysis using MySQL workbench). After loding the file, I performed data preprocessing. Since I was focusing on only commercial airlines, I removed all the rows that are not commercial and filled all the missing values of airport column with "Unknown". After the preprocessing stage, I created a dataframe for my data and created a lookup table condition. Finally, after creating all the tables, we perform the necessary analysis to find the top 10 airlines with greatest incidents, Displaying flights with above average number of bird strike incidents, displaying bird strike incidents by month and year.

## WHAT THIS PROJECT REPOSITORY CONTAINS.
This project contains the Rmd notebook with the SQL code.
