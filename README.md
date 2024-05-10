# Host a static website on AWS S3 private bucket and cloudfront

- step 1: create an s3 bucket 

![](images/s3-bucket%201.jpg)

- step 2: configure the bucket to allow public access

![](images/s3-bucket%202.jpg)

- step 3: upload files and folder

![](images/s3-bucket%203.jpg)

- step 4: go to cloudfront, create a distribution and configure the settings;
- add origin domain
- change origin access to origin access control
- create new OAC
- enable security protection
- enter index.html into default root object
- create distribution

![](images/s3-bucket%204.jpg)

-step 5: copy policy, go back to the bucket created, in permissions edit the bucket policy

![](images/s3-bucket%205.jpg)

- step 6: go back to cloudfront and copy the domain URL and check it on the browser to confirm access to your website

![](images/s3-bucket%206.jpg)