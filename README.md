# getSmartMeterAttachments
Copy all py to local directory
pip install the following:
 -  google-api-python-client 
 -  google-auth-httplib2 
 -  google-auth-oauthlib

setup a google gMail api and OAuth authentication for a project on console.cloud.google.com (see https://www.youtube.com/watch?v=I5ili_1G0Vk&t=0s)
save the OAuth client token and put into script, line 62

python sync.py once to create the inital tokens needed for authent
python sync.py to download attachments

main code courtesy of https://learndataanalysis.org/source-code-save-gmail-email-attachments-with-gmail-api-in-python/
