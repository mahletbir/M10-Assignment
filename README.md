# M10-Assignment
In oreder to scrape charities-bureau website, I will create web-scraper to load csv file into S3 Bucket and I will update web-scraper to iterate all results and load csv file into S3 Bucket.

In this lab, selenium  will be used to scrape a charities-bureau website and store the file in an s3 bucket.
To complete this assignment,I  will need to configure and install dependencies like awscli, boto3, time,s3fs and pandas dataframe.
 
<img width="941" alt="image" src="https://user-images.githubusercontent.com/91334065/162638668-f0f19e39-7c98-433a-ab62-ec34779221be.png">

Part 1：

Step 1. Load the script, M10_webscraper_assignment.ipybn, into my repository as a separate file.

Step 2. Create an s3 bucket to store my outputs of csv files.

Step 3. Update the script that was provided to remove the blank row in the csv output file.

Step 4. commit the changes to the script in the master branch of my GitHub repository

Part 2:

Alter the script, M10_webscraper_assignment.ipybn, to iterate through the pagination that exists on the page and compile all of the results in one dataframe from each page. Once I have done that, I should follow the same procedures in (2) to load the full csv file into the s3 bucket. Once the test has passed, commit the changes to the master branch of my GitHub repository, updating the script and load the file on s3.
