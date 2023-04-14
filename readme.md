# Documentation

## [Login](https://api.xgorn.tech/login)

## [Register](https://api.xgorn.tech/register)

### Ouo Bypass:
Path: /ouo_bypass
Method: GET
Arguments: url
Example:
```
import requests

api_key = 'your_api_key'
url = 'https://ouo.io/4ZuwGMc'

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/ouo_bypass', params=params)
json = get.json()
print(json)
```

### Mirrored Bypass:
Path: /mirrored_bypass
Method: GET
Arguments: url, host
Example:
```
import requests

api_key = 'your_api_key'
url = 'https://www.mirrored.to/files/083K7LQU/Youkoso.Jitsuryoku.Shijou.Shugi.no.Kyoushitsu.e.full.3693755-2.jpg_links'
host = 'sendcm'

params = {'api_key': api_key, 'url': url, 'host': host}

get = requests.get('https://api.xgorn.tech/mirrored_bypass', params=params)
json = get.json()
print(json)
```