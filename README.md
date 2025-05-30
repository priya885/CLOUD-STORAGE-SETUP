# CLOUD-STORAGE-SETUP

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: PRIYADHARSHINI B L

*INTERN ID*: CT04DF413

*DOMAIN*: CLOUD COMPUTING

*DURATIONS*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

# Task Description: Cloud Storage Setup

*As part of my internship project, I was given a task to set up and configure cloud storage using either AWS S3 or Google Cloud Storage. I decided to go with Google Cloud Platform (GCP) because it felt easier to use and I was already familiar with it from my previous tasks*.

The main objective was to create a storage bucket, upload a few example files, and manage the access permissions for those files.

*STEP 1*: Creating the Bucket
I first logged into my Google Cloud account and opened the Cloud Storage section. Then I clicked on Create Bucket. While creating the bucket, I had to give it a unique name (since bucket names must be globally unique). I chose the storage class as Standard and selected the location as Multi-region to make sure the files are accessible with better performance.

I didn’t change much of the default settings, as this task was for learning purposes.

*STEP 2*: Uploading Files
Once my bucket was created, I uploaded just one file to test if the upload works properly. I added a PNG image file from my computer. This was just to check how the cloud storage handles files and to show that it's working.

I clicked on the “Upload Files” button inside the bucket and selected the image. After a few seconds, the file appeared in the bucket, which means the upload was successful.

*Step 3*: Setting Permissions
The next part of the task was to change the access permissions for the files. By default, all the files in the bucket are private. To test the permissions feature, I selected one file and made it public so that anyone with the link could view it.

To do that, I went to the permissions tab of the file, clicked on “Add,” and gave the “allUsers” group Viewer access. I also explored how the IAM roles work and understood the difference between Viewer, Editor, and Owner roles.

*FINAL DELIVERABLES*

I took screenshots of:

The created bucket

Uploaded files in the bucket

Permission settings showing public access

I uploaded all the screenshots in my GitHub repository and wrote a small README file to explain the steps I followed.

*CONCLUSION*

This task helped me understand how cloud storage works and how files can be uploaded and shared through a cloud platform. Even though it didn’t involve any coding, it was still a good learning experience for using cloud services in real life.
