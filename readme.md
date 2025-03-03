# Deploying Node or Java App using Elastic Beanstalk LAB

## Overview

Deploy a basic Node.js or Java application using AWS Elastic Beanstalk. This lab demonstrates the complete deployment workflow—from code versioning in GitHub and packaging the application as a source bundle to deploying via Elastic Beanstalk using an S3 URL. Optionally, you may build an automated CI/CD pipeline that packages and uploads your code to S3.

## Tasks:

- Commit application code to a GitHub repository
- Ensure the repository contains all necessary files (e.g. package.json for Node.js or the appropriate build files for Java)
- Application must also be zipped and uploaded to S3 Bucket (can be done manually or automatically via pipeline)
- URL of S3 bucket must be supplied to Elastic Beanstalk

## Note:

- Deploy Node or Java App based on your primary specialization
- Use of database with application is not required
- Build a pipeline that zips application code and uploads to S3 bucket (optional, but will warrant additional marks if successfully executed)

## Screenshots

### Manual Code Zip File Upload to S3 Bucket

<img width="959" alt="Image" src="https://github.com/user-attachments/assets/352a293b-b7e0-4391-8762-d6aa9b6f26d9" />

### Elastic Beanstalk Deployment

<img width="959" alt="Image" src="https://github.com/user-attachments/assets/3a65534d-d437-4842-8cd4-05da180895f9" />

### Deployed web server

<img width="957" alt="Image" src="https://github.com/user-attachments/assets/b44a1637-b1e5-4eb4-ab12-243e68ea5b92" />

### CI/CD pipeline that packages and uploads code to S3 from Git Repo and deploys using elastic beanstalk

<img width="959" alt="Image" src="https://github.com/user-attachments/assets/60c3d833-1f9b-43a5-82d4-3253edc1a90b" />

### Artifacts in bucket

<img width="959" alt="Image" src="https://github.com/user-attachments/assets/3fd37445-a427-4d37-acb9-ddc3fd9473b1" />
