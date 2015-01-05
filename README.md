Cherrypy-curl
=============


This is a simple python 2.7 cherrypy web framework based web application hosted on Openshift to get website metrics using curl command.

openshift web url:

http://cherrypy-helloworldcurl.rhcloud.com/

Curl command on Terminal(your PC):

curl -X POST -d "website=http://www.google.com/" "http://cherrypy-helloworldcurl.rhcloud.com/test/"

Output: 

Metrics For http://www.google.com/

time_total = 0.148
http_code = 200
http_connect = 000
time_namelookup = 0.009
time_connect = 0.048
time_appconnect = 0.000
time_pretransfer = 0.048
time_redirect = 0.000
time_starttransfer = 0.108
size_download = 17411
size_upload = 0
size_header = 800
size_request = 177
speed_download = 117835.000
speed_upload = 0.000
 
