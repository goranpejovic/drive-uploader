# drive-uploader
Google Drive Python Uploader script

Should work on python 2.6 and 2.7. Python 3 not tested.

Use this script to upload files to Google drive.
Get OAuth 2.0 keys from https://console.developers.google.com/
Create new Project, enable Drive API, go to Credentials, create new OAuth 2 credential and download JSON. Place it in same folder as script and rename it to "client_secrets.json"

First time you run Uploader it will ask you to paste URL in web browser and ask you to paste String from the browser back to the script. It will store authentication token in ~/.credentials/python-gdrive.json.

**Dependencies**
install google-api-python-client using pip or easy install:
easy_install --upgrade google-api-python-client

use ./upload.py -h to see flags
