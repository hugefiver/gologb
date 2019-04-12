# Get User Webos

* PATH: `user/webos`
* Method: `get`

## Query

* `before` datetime: 仅显示该时间以前的，`count`字段随之变化。
* `after` datetime: 仅显示该时间后的，`count`字段随之变化。
* `limit` int: 列表最大数量限制，默认为20，不影响`count`字段。
* `all` bool: 获取全部。
* `likes` bool: 获取like数，默认`1`。
* `view` bool: 获取view数，默认`1`。
* `text` string|bool:
  * `0`： 不显示简要内容。
  * `pain`: 纯文本。
  * `html`: html文本。

## response

Type: `json`

```json
{
    "count": 10,
    "webos": [
        {
            "weboid": 1, // webo id
            "text": "", // 简要内容
            "likes": 0,
            "views": 0
        },
        {
            "weboid": 2, // webo id
            "text": "", // 简要内容
            "likes": 0,
            "views": 0
        }
    ]
}
```