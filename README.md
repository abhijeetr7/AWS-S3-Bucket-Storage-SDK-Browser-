# AWS-S3-Bucket-Storage-SDK-Browser

This project provides a web interface where you can:

Configure AWS: Enter your AWS Access Key ID, Secret Access Key, Region, and S3 Bucket Name.

Upload Files: Select a file from your local machine and upload it to the configured S3 bucket.

List Files: View a list of all objects (files) currently in your S3 bucket.

Download Files: Click the "Download" button next to a listed file to download it to your computer.

Delete Files: Click the "Delete" button next to a listed file to remove it from your S3 bucket.

To use this project:

Save the code: Save the entire code block above as an .html file (e.g., s3_sdk_demo.html).

Open in Browser: Open the s3_sdk_demo.html file in your web browser.

AWS Setup:

Create an S3 Bucket: Go to your AWS Management Console and create an S3 bucket (e.g., my-browser-s3-demo). Ensure the bucket name is globally unique.

Create an IAM User (for demo purposes only):

Go to IAM > Users > Add user.

Give it a name (e.g., s3-browser-user).

Select "Access key - Programmatic access".

Attach policies directly: Search for and attach AmazonS3FullAccess (again, this is for demo; in production, use a more restrictive policy).

Complete the user creation. Copy the Access Key ID and Secret Access Key immediately, as you won't see the Secret Access Key again.

Run the Demo:

In the web page, enter your copied AWS Access Key ID, Secret Access Key, the Region where your bucket is located (e.g., us-east-1), and your S3 Bucket Name.

Click "Configure AWS".

You can now use the Upload, List, Download, and Delete functionalities.

Remember to delete the IAM user and S3 bucket after you are done with the demonstration to avoid unnecessary charges and security risks.
