# RESTful Tutorial

## Python

```
import request

r = requests.post('http://httpbin.org/post', json={"key": "value"})
r.status_code
r.json()

```

Handling JSON

```
import json

JSON = json.loads( '{ "name":"John", "age":31, "city":"New York" }') # decoding json, gives dict

a = {"name" : "jaco"}
JSON2 = json.dumps(a)      # encoding json, gives string


```

## Nodejs

```
```
