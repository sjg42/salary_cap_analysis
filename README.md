# salary_cap_analysis

Project #2 - ELT: Salary Caps in American Professional Sports - MLB vs NFL

Team DELTA Project Proposal

SET UP:  As Data Analysts at a sports management firm, we have been tasked to study the salary cap data between the MLB and NFL over the last year with the intent of determining which sports teams the firm should focus on recruiting new athletes for. 

RESEARCH/DATA EXTRACTING: Historical data will be pulled from (a) source(s) focused on the NFL and then separately for the MLB. 

DATA CLEANSING/TRANSFORMING: The respective data will then be cleansed for the purpose of identifying any trends in a specific sport that would allow the firm to predict the most profitable sport/position(s) in the sporting industry. 

DATA LOADING: Once the data has been cleansed and format confirmed, it will be loaded into a single database to more easily analyze in the future. 

REFERENCES:

https://databases.usatoday.com/mlb-salaries-2022/page/1/

https://www.spotrac.com/nfl/cap/2022/


## ETL Files 

* Samik_MLB_2022.ipynb - scrapes MLB data from USA Today database and creates "2022 MLB Salaries.csv"

* project 2 - 2022salaries.ipynb - scrapes NFL data from Spotrac.com and creates "TeamSal22.csv"

* ProSportsSalaryCaps_MLB-NFL.ipynb - takes in data from two csvs above and cleans and loads data to Mongo Client database

* nfl_mlb_caps.csv - MongoClient database consists of salary data from all Professional American NFL and MLB teams across the country for the year of 2022


