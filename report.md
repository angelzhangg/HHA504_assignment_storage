## Objective
The objective of this assignment is to familiarize you with cloud storage services in Azure and Google Cloud Platform (GCP). You will learn how to upload files to Azure Blob Storage and GCP Cloud Storage using both Python and the platform's GUI.

## Instructions

### 1. Upload Files Using the GUI
- **Azure Blob Storage:**
  - Navigate to the Azure portal and create a new Storage Account.
    
![storage](https://github.com/user-attachments/assets/757046da-db21-4485-8054-5bcd12bdad17)
![storage2](https://github.com/user-attachments/assets/584c2897-2ee9-485c-8603-1ba123e06e40)
  - Create a Blob container within the Storage Account called test data.
    
![blob container](https://github.com/user-attachments/assets/67383654-eb93-49fc-a13c-84174080d8c6)
  - Upload a sample file (e.g., a text file or image) to the Blob container using the Azure portal.

![upload file](https://github.com/user-attachments/assets/8cabe5bf-c88f-4585-8490-ff89d3e0b6df)

- **GCP Cloud Storage:**
  - Access the Google Cloud Console and create a new Cloud Storage bucket.
    
![gcp storage](https://github.com/user-attachments/assets/f573ded4-249b-447d-a7ab-40a485ef4130)
  - Upload a similar sample file to the bucket using the GCP Console.
    
![gcp storage2](https://github.com/user-attachments/assets/52d337b5-a184-45ba-a5b2-24f68f8465b0)


### 2. Upload Files Using Python
- For this section, if you want to make it more realistic, I recommend finding some open source open source x-ray images and uploading them to the cloud storage. This though is not a requirement, just a suggestion. Potential sites where you can find medical images: 
  - [Stanford - Center for Ai and Machine Learning](https://aimi.stanford.edu/shared-datasets)
  - [Kaggle - Xray COVID images](https://www.kaggle.com/datasets/andyczhao/covidx-cxr2)
  - [NLM - Open Access Biomedical images search engine](https://openi.nlm.nih.gov/)
  - [Cancer - Imaging Archive](https://www.cancerimagingarchive.net/browse-collections/)
- **Azure Blob Storage:**
  - Write a Python script that uploads a file to the Blob container you created. Use the `azure-storage-blob` library to handle the upload.
- **GCP Cloud Storage:**
  - Write a Python script that uploads a file to the GCP Cloud Storage bucket you created. Use the `google-cloud-storage` library to handle the upload.

### 3. Explore Storage Features
- **Azure:**
  - Explore and document the options for managing and securing data in Azure Blob Storage (e.g., access policies, tiers).
- **GCP:**
  - Explore and document the options for managing and securing data in GCP Cloud Storage (e.g., IAM permissions, lifecycle rules).
