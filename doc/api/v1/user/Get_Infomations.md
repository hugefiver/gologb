# Get User Infomations

* PATH: `user/{user_id}/info`
* Method: `get`

## response

Type: `json`

```json
{
    "error": 0,
    "info": {
        "name": "",
        "favtar": "{link}",
        "errmsg": ""
    }
}
```

* error code:
  * `1`: user not found
  * `2`: user secure setting not allow check