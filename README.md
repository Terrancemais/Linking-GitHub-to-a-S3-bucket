# Using AWS Codepipeline to move a project code from GitHub to S3 Bucket
This Project was practice using a AWS Codepipline to automate a static website on AWS S3. Every part of this project was example code.

**
Steps:**
1. Create a simple index.html file on the local host and commit/upload it to your GitHub repository.
2. Create S3 bucket.
3. Configure the bucket to allow public access & upload the index file to the bucket.
4. Allow for static website hosting on the bucket.
5. Create a pipeline using AWS code pipeline.
6. Configure GitHub as the source provider and connect to your GitHub account.
7. Add the repository with the index.html file in it to the pipeline.
8. Add Amazon S3 as the deploy provider and select the bucket with the index.html file in it. Make sure to allow for the file to be extracted before being deployed.
9. Create the pipeline. It will take a few seconds for it to be deployed.
10. Test the pipeline by uploading a change to the index.html file to the GitHub repository.
