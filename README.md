# README for AWS S3 ACCESS AND IAM TASKS

## Overview
This repository contains IAM user policies for different tasks These resources are essential for managing AWS bucket access and identity centre

### Task 1: S3 Access and File Deletion Policy

#### Objective
Define an IAM user policy that allows for:
- Listing files in any S3 bucket that contains the word `spark-job`.
- Deleting files in the `spark-job-data-input` bucket within the `dumps` folder, excluding files that end with `.csv`.

### Task 2: IAM User Creation Policy

#### Objective
Create a policy that allows the IAM user to:
- Create new IAM users only if their usernames start with the word `engineer`.

### Task 3: Listing  AWS Resource ARN 

#### Question
List the ARN format/pattern for the following AWS resources:
- S3 accesspoint
- S3 bucket
- S3 storagelensgroup
- S3 object
- IAM mfa
- IAM role
- IAM user
- EC2 elastic-ip
- EC2 fleet
- EC2 instance
- EC2 image
