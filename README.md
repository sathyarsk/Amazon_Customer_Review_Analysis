# Amazon_Customer_Review_Analysis
Data pipeline for Amazon Customer Review Analysis
Datacleaning.ipynb
Initially created a AWS S3 bucket and uploaded the given parquet file.
Using pyspark aceesed the file cleaned and tranformed the file and loaded back to AWS S3.
Loadandanalyze.ipynb
Created an AWS RDS database  named "sathya-database".
Created a well defined database schema with table name "review" under database name "reviewdatabase".
Created indexing on table review with required attributes for better optimization.
The cleaned parquet file is loaded to AWS RDS using python pandas code with required database connections.
Performed the required analytical oprations using mysql query.
Added powerbi insights.
Added powerpoint presentation for this project.
