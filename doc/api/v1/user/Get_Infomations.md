# Get User Infomations

* PATH: `user/{user_id}/info`
* Method: `get`

## response

Type: `json`

```json
{
    "error": 0,
    "errmsg": "",
    "info": {
        "name": "",
        "favtar": "{link}"
    },
    "panel_details": {
        "articles": 0,
        "webos": 0,
        "following": 0, // This user following
        "followed": 0 // Following this user
    }
}
```

* error code:
  * `1`: user not found
  * `2`: can not see user info