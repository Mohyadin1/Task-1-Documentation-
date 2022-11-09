Investigate 3 different ways of hosting a static content website on Google Cloud using a Google Cloud service other than Compute Engine.

1) App Engine: This is a fully managed platform used for developing and hosting web applications. 
- Other than Compute Engine, you can use App Engine to host static websites, one benefit to it is that it can cost less than using a traditional hosting provider - as App Engine provides a free tier. 

Using App engine can allow you to create and deploy any type of web page, you can create your page using a HTML editor (or you can do it directly) then upload the html file into App Engine. Along with HTML you can also join together with CSS and javascript. 

I would use it for many reasons such as:
- It's fully managed 
- It's on a pay as you go model - meaning that you pay for what you use 
- Able to scale automatically  
- It's secure 
- Remote access 
- Can help with your savings as the prices are flexible, and your resources can scale up and down based on the app's usage 
- Good for start ups or individuals 

Reasons why I wouldn't use it would be:
- It stays with App Engine, cannot be transferred to anywhere else
-  It can be expensive depending on the nature of your application
- It doesn't support all languges unlike Compute Engine where it does. 


2) Google Cloud Storage: You can build static websites such as blogs by just using GCS. Unlike App engine, this can only do static web pages and not dynamic as its content cannot contain server-side scripts such as PHP. 
To make a static site on GCS, you would have to:
1) Direct your domain to Google cloud storage
2) then create the bucket that is connected to your domain
3) upload and share your sites files by directly uploading files using the google cloud console
4) After that you should check your access control to make sure that your files are properly shared for access
5) Assign an index page suffix and custom error page to guide users better
6) Test the site

Reasons to use this:
- Hosting a static website on GCS is cheaper than doing it on a dedicated server or on a shared server such as App Engine
- Availabilty 
- Scalable 
- Able to access data anywhere 
- Has disaster recovery, all data is stored and backed up
- Low cost
- Data is protected

Reasons why I wouldn't use this:
- Hard to migrate data to another cloud provider 
- Lack of total control and customisation -  to your data storage set-up
- Contracts can be an issue as you may need to reduce it at some point so it can risk you paying for storage you're not using. 

3) Firebase: This a hosting service that can allow you to quickly deploy web apps and serve both static and dynamic content. 
To do this you will need to create a firebase project with a google account. Once you can log in you will be able to initialize a project and go through a process to set it up, then deploy it. Then you can, by choice, connect it to your domain (another process to do with DNS).

Benefits to using Firebase hosting:
- The hosting is free and it also provides by default a SSL certificate unlike other web hosting services that will charge you and make you pay extra for getting a SSL certificate. 
- Secure hosting 
- Easy to use and easy to set up

The downside to it is:
- It is mostly andriod centered
- The data migration is limited as it is all hosted on firebase 
- Doesn't work in all countries 

After going through all these options I decided that I would go with GCS as hosting a static website wouldn't be able to maximise the full benefit of other services such as App Engine, Firebase etc. As said before, it does depend on the nature of the site itself. However, if it is a site that is very simple, with just HTML and maybe CSS included, then it is best to stick with GCS. 




