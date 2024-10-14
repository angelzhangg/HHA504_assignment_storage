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

![blob_storage](https://github.com/user-attachments/assets/f0ea2537-7e24-4c7b-8508-0b4ef47541ce)
1. Copy code from "https://colab.research.google.com/drive/1-TiNuRFiGucvnLgTlyp4bsdtR4_TduAT?usp=sharing#scrollTo=ZKgCaehp9NqN"
2. Storage account > Access Keys > Update account URL link
3. Create "text" file > upload Access Key > Rename .env
4. "pip install azure-storage-blob azure-identity python-dotenv" 
5. Create "angela-data.txt" file
   
- **GCP Cloud Storage:**
  - Write a Python script that uploads a file to the GCP Cloud Storage bucket you created. Use the `google-cloud-storage` library to handle the upload.
 
![python_cloud](https://github.com/user-attachments/assets/c5244154-1733-4fd1-be32-f954374dac55)
![python_cloud2](https://github.com/user-attachments/assets/1ef18c31-1aa8-413c-a4e6-fee117fb4a10)
![python_cloud3](https://github.com/user-attachments/assets/b91a94ad-d982-447e-b108-c3457049aeef)

1. Under IAM & Admin, create a service account.
2. Rovide a name under "Service account details"
3. Select "Compute storage admin" 
4. Click the 3 dots under Actions for the service account.
5. Click; Manage Keys. Add Key. Create New Key. JSON key type. Create. Download.

### 3. Explore Storage Features
- **Azure:**
  - Explore and document the options for managing and securing data in Azure Blob Storage (e.g., access policies, tiers).
    
![access policies](https://github.com/user-attachments/assets/652a604c-b2d1-425b-841b-bf01d71a482e)
1. Access controls->Shows current role assigments and eligible assignments
2. Check Access->Shows users/group access to the resouce

![role assignments](https://github.com/user-attachments/assets/66aaa0df-2316-425d-a1d2-3f8617099942)

3. Role Assignements-Shows the possible users and members that could be added

- **GCP:**
  - Explore and document the options for managing and securing data in GCP Cloud Storage (e.g., IAM permissions, lifecycle rules).
 
![permission](https://github.com/user-attachments/assets/92e7e427-ff8c-4e12-b94a-d4eee511859f)
![lifecycle](https://github.com/user-attachments/assets/dcbd1626-c264-4979-ba1f-e26b1d3955fc)
