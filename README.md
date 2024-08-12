this file is to explain the project and the compents of the work flow.
•	The company has a system for saving CSV files every 5 minutes, the files contain the main transactions process that the customers have completed.
•	I have built an ETL package that loads files in the destination database and makes the required transformations.
•	It was required to reject the record that has blank IMSI or CELL or LAC and redirect these records to a table in the database.
•	It was required to count the transactions on csv, count the transactions that loaded in the database, count the rejected records.
•	I have related the data loaded in the database with the CSV file then move the CSV file to other destination.
