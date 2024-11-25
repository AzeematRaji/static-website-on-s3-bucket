# Hosting a Static Website on AWS S3 with CloudFront as a CDN

- step 1: create an s3 bucket 

![](images/s3-bucket%201.jpg)

- step 2: configure the bucket to allow public access

![](images/s3-bucket%202.jpg)

- step 3: upload files and folder

![](images/s3-bucket%203.jpg)
![](images/udacity-cloud-005.png)

- step 4: go to cloudfront, create a distribution and configure the settings;
- add origin domain
- change origin access to origin access control
- create new OAC
- enable security protection
- enter index.html into default root object
- create distribution

![](images/s3-bucket%204.jpg)

![](images/udacity-cloud-003.png)

-step 5: copy policy, go back to the bucket created, in permissions edit the bucket policy

![](images/udacity-cloud-007.png)

- step 6: go back to cloudfront and copy the domain URL and check it on the browser to confirm access to your website

![](images/udacity-cloud-002.png)

- step 7: accessing via S3 object URL

![](images/udacity-cloud-001.png)