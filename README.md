## Quick Setup for Google Big Query for Personal Use for Windows OS

This tutorial will get you up and running with Google BigQuery in about 10 minutes. Enjoy!

### Install Python Library
Open Command Prompt and run the following script to install the Google BigQuery python library.
```pip install --upgrade google-cloud-bigquery```

### Sign Up for Free Trial

Google currently offers credit for the first 12 months to use some of their cloud products and services for free. Google will not charge your account, unless you manually sign up for the non-trial products or services.

### Create Service Account Key

1. From the drop-down menu, select “New Service Account”.   

2.Enter in a Service Account name. 

3. For the “Role” select Project and then Owner.

4. Click on Create and a local JSON file will be created with the credentials. This file will show up in your “Downloads” folder, I would recommend moving this file to a location that is secure. 

### Environment Variable

1. Go to System Properties
2. Set “Variable Name” to GOOGLE_APPLICATION_CREDENTIALS.
3. Set Variable value to the location of the file.

[Link](url) and ![Image](src)


### Test BigQuery Connection




Happy Querying!
