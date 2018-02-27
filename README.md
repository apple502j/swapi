Scratch Wiki API.
for example, "Get Featured Article in Japanese Scratch-Wiki" is:
```
import requests
json=requests.get("https://raw.githubusercontent.com/apple502j/swapi/master/featured/ja.json").json()
print(json["featured"]["2018"]["3"]["article"])
```
returns "緑の旗"
