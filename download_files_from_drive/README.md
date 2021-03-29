# download files from drive 
Code for using PyDrive to download files from google drive to your local computer in python. <br />
Steps work with PyDrive: 
 1) Follow the instructions on the [PyDrive page](https://pythonhosted.org/PyDrive/quickstart.html) to download a JSON key. 
    - Make sure you don't download a service account JSON key. This needs to be an OAuth client ID for use with a Web application. 
    - Add the key to your home directory and rename it client_secrets.json 
 2) Enable the Google Drive API for your project 
    - As of 02-21-2021, this can be found in APIs & Services --> Library --> search for "google drive" 
 3) Add yourself as a test user using your gmail account that you want to connect to google drive with
    - As of 02-21-2021, this can be found in APIs & Services --> OAuth consent screen --> scroll down to "Test users"
