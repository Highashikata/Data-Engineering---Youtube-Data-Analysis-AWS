# Data-Engineering---Youtube-Data-Analysis-AWS
In this project, we will analyse youtube videos database for a marketing purpose. In order to allow our customers to make the choice on which YT video should I choose to put my ad campaign on and so on and so forth.

The requirements from our customers:
  - Launching new data-driven campaign.
  - Main advertising channel : Youtube Ads.
  - Initial questions to answer:
    - How to categorise Youtube videos, based on their comments and statistics (views, channels subsribers ...) ?
    - What factors affect how popular a YT video will be ?

Why choosing Youtube as a channel Campaign.
  Because it's the second most-visited website in the world. 34.6 billion visitors per month.
  
  
##### Goals and Success Criteria 
How will I measure the success of my project.

1. **Data Ingestion** : Ingest Data, one-offs and incrementally.
2. **Data Lake** : Design and build a new Data Lake Architecture.
3. **AWS Cloud** : We will be using AWS as the cloud service provider.
4. **ETL Design** : Extract, Load, Transform Data efficiently.
5. **Scalability** : The Data architecture should scale efficiently.
6. **Reporting** : Build a Business Intelligence Dashboard (Power BI, Tableau, Google Data Studio).

##### The Data we will be using
In this project we'll use the YouTube trending videos Dataset from Kaggle.
We will collect the Data using the YouTube API.


##### Vocabulary Along the Project

Region: Physical locations where AWS has Data Centers.
AZ : One or more discrete Data Centers with redundant power, networking and connectivity in AWS region.

##### How to get our Data

- first we will download the data needed from kaggle, and here is the link: https://www.kaggle.com/datasnaek/youtube-new
- Then we will create a AWS S3 Bucket.
- Finally, we will copy the Data to S3, using aws cli.

