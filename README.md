# Automation in Google Cloud using  Python - IAM Service Accounts - Parte 1

Pre-requisites:
1) Install Python

Link for download and installation procedure in Windows:
https://www.python.org/ftp/python/3.8.7/python-3.8.7-amd64.exe

Link for download and installation procedure in Linux:
https://www.python.org/downloads/source/

Link for download and installation procedure in MacOs:
https://www.python.org/downloads/macos/


Macro Step

Step 1) Install and Configure the Cloud SDK on your laptop

https://cloud.google.com/sdk/docs/quickstart#windows

https://cloud.google.com/sdk/docs/quickstart#mac

https://cloud.google.com/sdk/docs/quickstart#linux

Step 2) Create a Service Account (IAM > Service Account)

Name: automation

Role: Storage Admin

Step 3) Create and download a Key (JSON format) for the Service Account (IAM > Service Account > automation > Add Key)

Step 4) Download Python script

curl -O https://storage.googleapis.com/bootcamp-gcp-public/lista_storage.py

Step 5) Install Python libraries from Google Cloud Storage service on your laptop

NOTE: YOU WILL NEED PYTHON/PYTHON3 AND PIP/PIP3 INSTALLED ON YOUR LAPTOP BEFORE PROCEEDING.

Alternative 1
pip3 install --upgrade google-cloud-storage

Alternative 2
pip install --upgrade google-cloud-storage

Step 6) Create a new Cloud Storage test bucket