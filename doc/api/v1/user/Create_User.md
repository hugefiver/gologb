# Create User

* PATH: `user/create`
* Method: `post`
* Type: `json`

## request body

```json
{
    "name": "",
    "email": "",
    "info": {}
}
```

## response

```json
{
    "error": 0,
    "body": {
        "id": 1,
        "errmsg": ""
    }
}
```

* error code:
  * `1`: name used
  * `2`: email used
  * `3`: info not complete
  * `15`: create failed