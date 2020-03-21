## Quick Setup for Google Big Query for Personal Use for Windows OS

This tutorial will get you up and running with Google BigQuery in just **10 minutes**. Enjoy!

### Install Python Library
Open Command Prompt and run the following script to install the Google BigQuery python library.<br/>
```pip install --upgrade google-cloud-bigquery```

### Sign Up for Free Trial

Google currently offers credit for the first 12 months to use some of their cloud products and services for free. Google will not charge your account, unless you manually sign up for the non-trial products or services. Sign up [here.](https://cloud.google.com/blog/products/gcp/try-google-bigquery-today-now-with-10gb-of-free-storage) <br/>

### Create Service Account Key

1. From the drop-down menu, select “New Service Account”.   <br/>

![New Service Account](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20Service%20Account.png)<br/>
2.Enter in a Service Account name. <br/>

![Service Account Name](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20Service%20Name.png)<br/>

3. For the “Role” select Project and then Owner.<br/>

![Role](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20Role.png)<br/>

4. Click on Create and a local JSON file will be created with the credentials. This file will show up in your “Downloads” folder, I would recommend moving this file to a location that is secure. <br/>

![](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20Create%20Local%20Json.png)<br/>

### Environment Variable

1. Go to System Properties and select "Environment Variables".<br/>

![System Proeperties](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20System%20Properties.png)<br/>

2. Select New.<br/>

![Image](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial%20New.png)<br/>

3. Set “Variable Name” to GOOGLE_APPLICATION_CREDENTIALS and set Variable value to the filepath.<br/>

![Image](https://github.com/elizkhan/CloudSetup/blob/master/GoogleTutorial.PNG)<br/>


### Test BigQuery Connection




Happy Querying!
