# Short_Article

## Article_Body

> `id`: int

id

> `poster`: int = `user.id`

发布者

> `datetime`: time

发布时间

> `text`: string

文本内容

> `image`: file

图片

> `comments`: int => [`comment body`](#comment_body)

评论

## comment_body

> `poster`: int = `user.id`

发布用户

> `reply`: int = `comments&`

回复楼层

> `datetime`: time

发布时间

> `text`: string

评论内容