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

### Tiktok Scrape:
Path: /tiktok_scrape

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://www.tiktok.com/@0906yu_rin/video/7103872167225363713?_r=1'

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/tiktok_scrape', params=params)
json = get.json()
print(json)
```

### Facebook Scrape:
Path: /facebook_scrape

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://www.facebook.com/kreatifpandaindo/videos/917251239418859/?mibextid=JgRRn7n7jRVACbyL'

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/facebook_scrape', params=params)
json = get.json()
print(json)
```

### Instagram Scrape:
Path: /instagram_scrape

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://www.instagram.com/reel/CqcUdr-ppgT/?igshid=YmMyMTA2M2Y='

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/instagram_scrape', params=params)
json = get.json()
print(json)
```

### Instagram Scrape v2:
Path: /instagram_scrapev2

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://www.instagram.com/reel/CqcUdr-ppgT/?igshid=YmMyMTA2M2Y='

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/instagram_scrapev2', params=params)
json = get.json()
print(json)
```

### Twitter Scrape:
Path: /twitter_scrape

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://twitter.com/TheRundownAI/status/1645291024367878144?s=20'

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/twitter_scrape', params=params)
json = get.json()
print(json)
```

### Twitter Scrape v2:
Path: /twitter_scrapev2

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://twitter.com/TheRundownAI/status/1645291024367878144?s=20'

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/twitter_scrapev2', params=params)
json = get.json()
print(json)
```

### Likee Scrape:
Path: /likee_scrape

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://likee.video/@MEKDede/video/7199606118785777185'

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/likee_scrape', params=params)
json = get.json()
print(json)
```

### Pinterest Scrape:
Path: /pinterest_scrape

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://id.pinterest.com/pin/738942251365909955/'

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/pinterest_scrape', params=params)
json = get.json()
print(json)
```

### Pinterest Scrape v2:
Path: /pinterest_scrapev2

Method: GET

Arguments: url

Example:
```
import requests

api_key = 'your_api_key'
url = 'https://id.pinterest.com/pin/738942251365909955/'

params = {'api_key': api_key, 'url': url}

get = requests.get('https://api.xgorn.tech/pinterest_scrapev2', params=params)
json = get.json()
print(json)
```