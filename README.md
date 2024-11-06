# Automating-Error-Report-Retrieval-and-Distribution

The task automates the download, cleanup, and distribution of error reports stored in an AWS S3 bucket, making data transfer efficient and less error-prone.
# Software Versions
1. Python: 3.x
2. AWS CLI: Latest version (required for S3 access)
3. Boto3: AWS SDK for Python
4. SMTP: Access to Gmail's SMTP server for sending emails

# Setup Instructions
### 1. Clone the repository

   git clone https://github.com/saiharshitha82/Automating-Error-Report-Retrieval-and-Distribution.git
  cd your-repository

### 2. Install the required libraries

python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

   
### 3. Download the dataset

The dataset (error_report.csv) is stored in an AWS S3 bucket. Download it by running fetch_csv.sh: bash fetch_csv.sh

# Project Structure

1. fetch_csv.sh: A shell script to download the error_report.csv file from the AWS S3 bucket and verify download success.
2. send_email.py: A Python script that cleans the downloaded CSV file and emails it as an attachment.

# Credits
This project was created by Sai Harshitha Mutyala (https://github.com/saiharshitha82) 
