# viva


import sys,os,os.path
os.environ['HTTP_PROXY']="http://proxy.example.com:80"
os.environ['HTTPS_PROXY']="https://proxy.example.com:443"


%env


import requests
requests.get("http://google.com")
