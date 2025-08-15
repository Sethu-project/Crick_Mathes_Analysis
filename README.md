# Crick_Matches_Analysis
IPL, One Day & Test Matches Analysis 

Process of Cricket Data Analysis

1. 3 Category of matches selected - IPL, One-day & Test.
2. Created 2 tables namely:
          match_summary has details of the match date, venue, team names, toss, player of the match etc.
          ball by ball delivery details has inning, batsman runs, extra runs, bowler, dismissal, fielder etc.
3. Primary Key has been assigned as match_id to match_summary table and this match_id is Foreign Key for other table ball by ball delivery   table.     
4. Tables with necessary columns has been created by way of VSCode.
5. Data for each category has been extracted from the given web-site in the project.
6. Available data was in json zip format and the same was un-zipped in a separate json folder.
7. Data frame created with Pandas, data checked, cleaned and processed for upload.
8. Processed data pushed to MySQL tables using python & VScode.  
9. Queries raised in sql for presentation data.
10. Power BI used for presentation of details in each category - IPL, One-day & Test matches.
