## Quick Setup for Google Big Query for Personal Use for Windows OS

This tutorial will get you up and running with Google BigQuery in just **10 minutes**. Enjoy!

### Install Python Library
Open Command Prompt and run the following script to install the Google BigQuery python library.
```pip install --upgrade google-cloud-bigquery```
![Image](src)

### Sign Up for Free Trial

Google currently offers credit for the first 12 months to use some of their cloud products and services for free. Google will not charge your account, unless you manually sign up for the non-trial products or services. Sign up [here.](https://cloud.google.com/blog/products/gcp/try-google-bigquery-today-now-with-10gb-of-free-storage) 

### Create Service Account Key

1. From the drop-down menu, select “New Service Account”.   

![New Service Account](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20Service%20Account.png)
2.Enter in a Service Account name. 

![Service Account Name](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20Service%20Name.png)

3. For the “Role” select Project and then Owner.

![Role](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20Role.png)

4. Click on Create and a local JSON file will be created with the credentials. This file will show up in your “Downloads” folder, I would recommend moving this file to a location that is secure. 

![](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20Create%20Local%20Json.png)

### Environment Variable

1. Go to System Properties

![System Proeperties](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20System%20Properties.png)
2. Set “Variable Name” to GOOGLE_APPLICATION_CREDENTIALS.

![Image](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20New.png)
3. Set Variable value to the location of the file.

![Image](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial.PNG)


### Test BigQuery Connection




Happy Querying!
