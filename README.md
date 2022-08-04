## Hello, I am Cliff Williams (aka Clifra Jones)  

I am a 30 year IT engineer, systems architect, administrator, cloud architect, Data Base Administrator and part time developer.

In my GitHub reposititories you mostly will find things related to System, Cloud, Networking, Networking as a Service, etc. Administration. 
Much of which is centered on automation. The majority of my repositories are PowerShell modules such as the Meraki API Powershell module that allows you to use PowerShell to administer a Meraki Network as a Service. Another small module is the AWS_Tools_AddOns which adds a few usefull function when working with AWS S3 in PowerShell (look for more to come here)

Most of these projects are free to use and modify to your taste. If you wish to contribute to any of these feel free to do so.

Note: These are not my day job. I am a busy IT guy in a large corporation with a personal life. If you report an issue with one of my project and I don't respond in a timely manor please bare with me. If you have the skills you more than welcome to suggest the fix!

# Projects
## [Meraki-API-V1](https://clifra-jones.github.io/Meraki-API-V1)
This is a PowerShell Module to manage Meraki networks and devices through the Meraki Version 1 API.  
Meraki is a Networking as a Service provider from Cisco. This module provides PowerShell function for all services provided by the API.
This module has been extensively used by our Networking/Infrastructure team and out Security team. 


## [Smartsheet (Alpha version)](https://clifra-jones.github.io/Smartsheet)
This is a PowerShell module to work with the Smartsheet API. 
This currently implements all functionality related to Sheets. I will be implementing projects amd dashboar dsupport in the near future.
This is an early alpha version so extensive testing has not been done.


## [MyAWSSecrets](https://clifra-jones.github.io/MyAWSSecrets)
This is a small VB.Net application that allows someone with an IAM user account in AWS to retrieve secrets from AWS Secrets Manager.
This application was specifically designed to address the issue of rotating AWS Access Keys. Our organization forces access keys to be rotated every 90 Days. We store the newly generated Access Keys in Secrets Manager as AccessKeyId and SecretAccessKey. This application allowes the user to retrieve their new keys. The Secret Name is stored in the users IAM account under the tag SecretName. This process has allowed us to no longer send .csv files to users in email that are uncontrolled.


## [Docusign-API](https://clifra-jones.github.io/Docusign-API)
This is a PowerShell module to work with teh Docusign API.
This module was built to address a specific need in our orgnaization. I have implemented the OAuth authentication and the Envelope features of the API as PowerShell functions. further implementation of API function will be  comming later.


<!---
Clifra-Jones/Clifra-Jones is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
