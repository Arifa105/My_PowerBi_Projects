# 1. Revenue Insights in Hospital Domain (PowerBI — Excel):

## information regarding the columns described in the CSV files
1. dim_date
2. dim_hotels
3. dim_rooms
4. fact_aggregated_bookings
5. fact_bookings

# Connect Data source(csv, and xl files-> transformation (power query) -> DAX ->Dasboarding

group them into seperate categories
                      
DAX: where you create new columns 
(1) calculated column
(2) measures

wn = WEEKNUM(dim_date[date])  #new col
day_type = WEEKDAY(dim_date[date])   #new col

#enter (ALT+ENTER)
var wkd = WEEKNUM(dim_date[date]) 
return if (wkd>5 ,"weekend", "weekday")



# 2. Sales Insights Dashboard (PowerBi and SQL)
Following steps that have done.

  1- Requirement gathering.
  
  2- Data Collection
  
  3- Data prepration
  
  4- Data Modeling
  
  5- Dashboard Building
  
  6- Deployment

