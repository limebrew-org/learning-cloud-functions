# Learning-cloud-functions
Learning Cloud Functions using Google Cloud using Flask to list all DNS records in a Google Cloud Project

## Prerequisites
The prerequisites for this project are:

- Python 3.8 or higher
- A python virtual environment preferably to install dependencies specific to the project
- A valid google cloud project with a cloud function API enabled with a billing account connected
- A service account with IAM permission: DNS Reader
- Environment variables:
    - GCLOUD_PROJECT_ID=your-google-cloud-project-id
    - GOOGLE_APPLICATION_CREDENTIALS=absolute-path-to-your-service-account-key-file

## Installation
To install the dependencies, use the following command:

    pip install -r requirements.txt

## Run 
To run the cloud function locally, open a terminal from the project folder and run the following command:

    functions-framework-python --target get_dns_records

To access the cloud function that is running locally at port 8080, you have to use:

    curl http://localhost:8080

