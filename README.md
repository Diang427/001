# 001
z
import requests
 
headers = {'Authorization': 'token %得到的40位Token%'}
 
r = requests.get(url,headers=headers)
if(r.status_code != 404):
