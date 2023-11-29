import os
os.environ['http_proxy']= "http://user:passwd@host:port"
os.environ['https_proxy']= "https://user:passwd@host:port"
os.environ['HTTP_PROXY']= os.environ['http_proxy']
os.environ['HTTPS_PROXY']= os.environ['https_proxy']

%env


import requests
requests.get("http://google.com")
