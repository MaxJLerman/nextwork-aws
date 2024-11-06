# Project #2: Visualise Netflix Data using Amazon QuickSight

Amazon QuickSight helps you analyse data and create visualisations easily. This project will teach you to analyse a huge dataset of Netflix shows and movies to create a dashboard that extracts all the insights. Even if you're not familiar with data analysis, Amazon QuickSight is designed to be beginner friendly. This is the final product:

![final product](https://learn.nextwork.org/projects/static/aws-analytics-quicksight/intro-1.1.png)

In this project, you will:

1. Upload a dataset into an S3 bucket
2. Create an account on Amazon QuickSight
3. Connect your dataset (in the S3 bucket) to Amazon QuickSight
4. Create a variety graphs, charts and analysis using QuickSight
5. Publish a dashboard full of insights into your dataset

## Step 1: Download neccessary files

Save the following files by right-clicking and selecting _save link as_:

- [`netflix_titles.csv`](https://storage.googleapis.com/nextwork_course_resources/courses/aws/AWS%20Project%20People%20projects/Project%3A%20Visualise%20Data%20using%20Amazon%20QuickSight/netflix_titles.csv) contains all the data to be analysed
- [`manifest.json`](https://storage.googleapis.com/nextwork_course_resources/courses/aws/AWS%20Project%20People%20projects/Project%3A%20Visualise%20Data%20using%20Amazon%20QuickSight/manifest.json) for

## Step 2: Store the dataset in an Amazon S3 bucket

- [Log into your AWS account](https://signin.aws.amazon.com/signin?redirect_uri=https%3A%2F%2Fconsole.aws.amazon.com%2Fconsole%2Fhome%3FhashArgs%3D%2523%26isauthcode%3Dtrue%26state%3DhashArgsFromTB_ap-southeast-2_fffdf5be4bb1a27e&client_id=arn%3Aaws%3Asignin%3A%3A%3Aconsole%2Fcanvas&forceMobileApp=0&code_challenge=m-aiqeB2UZeXTGXNyugMP8L64zd_AGUxJl4HLnA-X1o&code_challenge_method=SHA-256)
- Navigate to the **S3 Console**
- Click **Create bucket**
- Name the bucket _nextwork-quicksight-practice_
- Keep the rest of the configuration the same and click **Create bucket**
- Upload the `netflix_titles.csv` and `manifest.json` files to the bucket
- Click the checkbox of `netflix_titles.csv` and click **Copy S3 URI**
