# README.md
VAhir  
May 27, 2016  

**What**   
The purpose of this project is provide insights into rolling sales data from 1 of the five boroughs of NYC - **Queens**.
Following transformation/formatting was done on this data :
  + a)  Date columns were converted to "YYYY-MM-DD" format.
  + b)  Missing values were identified and handled.
  + c)  Outliers were identified and handled.


**How**  
  Data for performing analysis is downloaded from following link :   
http://www1.nyc.gov/home/search/index.page?search-terms=Rolling+sales+update

The data from website is stored as "raw" data in Data directory of the project's repository.
Later R scripts are used to load this data, analyze it and then output formatted/filtered data.

**Directory Structure**  
Following is the directory structure for this project:  
  
             Root --> README.md
              |
              |------> Data
              | 
              |------> Analysis
              |
              |------> Paper
              
