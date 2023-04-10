# Marketing-Data-ETL

Using Snowflake and SQL, the goal of this exercise was to identify somewhat disengaged customers for a targeted marketing effort. Disengaged customers where defined as those who had not completed a transaction in the last 90 days. Before the data could be queried however, it needed to be cleaned. Upon initial investigation, there were may NULL values, duplicates, and a range of formatting inconsistencies for names, phone numbers, zip codes, etc. 


<img src="Resources/initial_table.png" width=75%>


Trimming leading and trailing spaces, standardizing Phone numbers, and splitting names into two collumns

<img src="Resources/trimming_name_phonenum.png" width=75%>
