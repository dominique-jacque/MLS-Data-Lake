# MLS-Data-Lake
MLS Data Lake Repository contains the setup_mls_data_lake.py script, which automates the creation of a data lake for MLS analytics using AWS services. The script integrates Amazon S3, AWS Glue, and Amazon Athena, and sets up the infrastructure needed to store and query MLS-related data.

## Overview

The setup_mls_data_lake.py script performs the following actions:

Creates an Amazon S3 bucket to store raw and processed data. Uploads sample NBA data (JSON format) to the S3 bucket. Creates an AWS Glue database and an external table for querying the data. Configures Amazon Athena for querying data stored in the S3 bucket.

## Architectural Diagram 
![image](https://github.com/user-attachments/assets/061b0fc9-cc3a-41d3-92bd-3d620326b7ef)
