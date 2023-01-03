# Youtube-Analysis

![aws](https://user-images.githubusercontent.com/60398030/210317423-e78c53b5-c537-439f-8557-1e43238c718a.png)

Motive: <br/>
--> To know how to categorise Youtube videos based on the comments and statistics i.e views, subsribers etc. <br/>
--> Factors affecting popularity of Youtube video. <br/><br/>
Process:
1) Uploaded the youtube data to an s3 bucket with CLI.
2) Created data catalog in AWS Glue with the crawler for different data files.
3) Converted JSON files to Parquet with AWS Lambda and created Trigger for s3 to automate the process for new data.
4) Built ETL with AWS Glue to join cleaned data and use it for reporting/analytics.
