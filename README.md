# STATIC WEBSITE HOSTING

## SUMMARY

This Project demonstrates how to set up a static website in S3 bucket using Amazon S3 Static Website Hosting.
It is another opportunity to familiarize with creating an S3 bucket, and learn how to upload static website content; HTML ,CSS files to the S3 bucket and configure the bucket to enable static website hosting.

To ensure the static website is accessible via the provided S3 bucket URL, the permissions settings is edited to allow public access.
A Bucket Policy is created to allow for “GetObject” for who needs to access the bucket.
Also, the ACL (Access Control List) is enabled to allow public permission to read objects in the bucket.
At the end of this project, we will verify that the static website is accessible via the provided S3 Bucket URL.

## Objective

* Create an S3 bucket

* Upload static website content

* Configure S3 for static website hosting

* Access the static website.

### Creating an S3 Bucket

We proceed to create an S3 bucket called staticbucket456

![alt text](<Images/Image 1.PNG>)

We upload content into our S3 bucket. This includes a html file and object into the bucket and configure the bucket for static website hosting. Also, configure the index document.

![alt text](<Images/Image 2.PNG>)

Accessing the website, we verify that the files uploaded are accessible using the provided endpoint and the contents displays correctly.

![alt text](<Images/Image 3.PNG>)

**Insights and Obsevations**

* S3 bucket Policy must be configured to allow access to the above bucket.

* For this bucket, we created a Bucket Policy to allow for “GetObject” for who needs to access the bucket.

* Also, the ACL (Access Control List) is enabled to allow public permission to read objects in the bucket. 

This project re-emphasizes the simplicity afforded by static website in manging and hosting content.



