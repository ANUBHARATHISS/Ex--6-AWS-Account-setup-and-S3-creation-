## Ex--2-AWS-Account-setup-and-S3-creation-
## Name : ANUBHARATHI SS
## Reg No : 212223040017
## Introduction

In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

## Objectives

- Create a Bucket in Amazon S3.
- Add Objects (files and folders) to the bucket.
- Access, move, download, and delete the objects.
- Delete the Bucket.

## Illustration

### Step 1: Choose S3 Service

Choose the S3 service from the list of services provided by AWS.

![WhatsApp Image 2025-11-16 at 3 13 12 PM](https://github.com/user-attachments/assets/c7b1d844-ae75-43e8-a93d-e70b7323bcdb)


### Step 2: Create a Unique Bucket

After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.

![WhatsApp Image 2025-11-16 at 5 01 41 PM](https://github.com/user-attachments/assets/80fc5442-a696-4e2e-aea8-41e03350b5a4)
![WhatsApp Image 2025-11-16 at 5 02 10 PM](https://github.com/user-attachments/assets/01506903-28f2-425f-8cc4-c9caf120dc6f)
![WhatsApp Image 2025-11-16 at 5 02 26 PM](https://github.com/user-attachments/assets/af8aef88-49eb-4799-9ff9-f92e0fc1fce8)
![WhatsApp Image 2025-11-16 at 5 03 01 PM](https://github.com/user-attachments/assets/cc7a6b4e-e89c-4522-952b-e822805031e1)
![WhatsApp Image 2025-11-16 at 5 03 26 PM](https://github.com/user-attachments/assets/58e3d31f-feba-41f3-b463-a4b041c9a9eb)


For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

### Step 3: Upload Files to the Bucket

Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

![image](https://github.com/user-attachments/assets/de51c34d-fb2b-4d74-89ba-eef97e5ef990)
![image](https://github.com/user-attachments/assets/3a137296-7bce-474e-9aee-90f1270da0b5)

You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., `https://s3-ap-southeast-2.amazonaws.com/...`) to share it.

![image](https://github.com/user-attachments/assets/9938ef1e-7e40-49e8-a44b-18c0610ecac4)
![image](https://github.com/user-attachments/assets/907b9eae-d631-4936-948b-81c2e5c4e5a2)


### Step 4: Upload a Folder

You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

![image](https://github.com/user-attachments/assets/f0ad8c4e-0d66-490f-a4e0-3ecc1d39ba25)

### Step 5: Delete the Bucket

To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

![image](https://github.com/user-attachments/assets/c09b5618-9d48-4d70-b59a-e76dd9c163f6)
![image](https://github.com/user-attachments/assets/28c379ea-5ad1-4056-bb86-cb79bd9a3fa7)

## Result

Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.
