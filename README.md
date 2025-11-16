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
![WhatsApp Image 2025-11-16 at 5 28 19 PM](https://github.com/user-attachments/assets/ef109c18-f360-497c-96bd-d80363655ea1)
![WhatsApp Image 2025-11-16 at 5 28 19 PM](https://github.com/user-attachments/assets/40c35225-813d-47d9-acd7-67ade14f88e6)



For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

### Step 3: Upload Files to the Bucket

Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

![WhatsApp Image 2025-11-16 at 5 06 30 PM](https://github.com/user-attachments/assets/75323663-1c1d-493f-afbd-c4a0b4c1d3fb)
![WhatsApp Image 2025-11-16 at 5 06 45 PM](https://github.com/user-attachments/assets/36e80324-69c9-4bfb-9c39-255c72d34416)


You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., `https://s3-ap-southeast-2.amazonaws.com/...`) to share it.

![WhatsApp Image 2025-11-16 at 5 10 22 PM](https://github.com/user-attachments/assets/c3be7d22-c7e9-44e9-a840-05d5575ea210)
![WhatsApp Image 2025-11-16 at 5 11 54 PM](https://github.com/user-attachments/assets/7a4b8299-399c-4267-a80b-4e3265bf6b7f)


### Step 4: Upload a Folder

You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.
![WhatsApp Image 2025-11-16 at 5 15 04 PM](https://github.com/user-attachments/assets/efaf15cf-9ab5-47c8-8cc4-902a54201cce)


### Step 5: Delete the Bucket

To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.
![WhatsApp Image 2025-11-16 at 5 15 04 PM](https://github.com/user-attachments/assets/6d4442de-ffa3-44d2-b9df-6641106e037e)


## Result

Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.
