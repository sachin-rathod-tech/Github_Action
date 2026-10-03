# GitHub Actions - Portfolio Deployment

My portfolio website, deployed automatically to **AWS S3** using **GitHub Actions**.

## How It Works

1. I push code to the `main` branch
2. GitHub Actions runs the **Portfolio Deployment** workflow
3. Files are synced to the S3 bucket
4. The website is updated

## Tech Stack

- GitHub Actions
- AWS S3
- HTML / CSS

## Setup

1. Create an S3 bucket and enable static website hosting
2. Add the bucket policy (`s3_bucket_policy.json`)
3. Add GitHub secrets: `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`, `AWS_REGION`
4. Push to `main` and check the **Actions** tab

## Author

Sachin Rathod - Cloud & DevOps Engineer
