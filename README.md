# ucm-to-webex-calling-migration

This code demonstrates the base API calls for enabling Webex 
calling and migrating users and device from on-prem UCM

It will focus on the Webex APIs, some AXL is included but most 
will be skipped as we focus on the new things

## Quick start
### Developer Sandbox
The demo is tested on a developer sandbox, you can get your own
at (try incognito mode if you get an error)   
https://developer.webex.com/docs/developer-sandbox-guide

Once created, you will receive all details including an admin 
username and password.  You can use this to login to   
https://admin.webex.com   
https://developer.webex.com


### Running the code
The code is made in a Jupyter Notebook, from within this base folder 
run 
```cmd
pip install -r requirements.txt
jupyter lab
```
This will start a server and open a browser window.  Just open 
the files you'd like to try and run. Some code will depend on 
previous bits, the files are numbered in the order they should be 
run

Note that pretty much all dependencies are for Jupyter Notebook, if you 
run the code on its own, only "requests" is required