# Portfolio_Hosting-on-docker

Created a portfolio using HTML, CSS and Javascript.
After successful creation of portfolio, Login to Aws console.
Search for S3 from the search box.
Click to create a bucket.
Select Region in my case it is {AsiaPacific(Mumbai)ap-south-1}.
Give the unique name of S3 bucket. Or you can choose existing bucket, if you have already.
Check object ownership(ACL enables), if it's publicly accessible over internet.
Check (uncheck) Block Public access setting to access over internet or manage it according to your need.
Enable/Disable bucket versioning to preserve, retrieve, and restore every version of every object stored in your Amazon S3 bucket.
Apply tags (optional)
Check Encryption default or customize according to your need.
(Put it default) or Click on advanced setting and customize according to your need.
and lastly click to create bucket.
Now, the bucket is successfully created.
click on created bucket.
click to upload.
click to add file or folder.
select the file and folder from your device and click to upload.
Now, click to close.
Now open your folder and click to properties.
Scroll down and go to static wbsite hosting section.
Enable static website hosting
Select Hosting type(static or redirected).
scroll down and Give the name of index document
Leave error document empty(optional).
Click to save changes.
Copy the index document link and paste it in browser.
Now, It's working.
