Direct fork of instaloader fixing the authentication issues extract your isntagram session id froma  web page
export SESSION_ID=<your session id>
remidner it doesn't have the trailing ; that's from the cookie seperator
then run instaloader as normal no need --login
I will add a patch that updates the session id from the env var that's it.
