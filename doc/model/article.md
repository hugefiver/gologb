# Article

## Article_body

> `id`: int

文章id

> `publish_time`: time

发布时间

> `edit_time`: time

最后编辑时间

> `music`: [`music body`](#music_body)

音乐

> `poster`: int = `user.id`

发布者

> `markdown`: string

md格式文章

> `html`: string

处理为html的文章

> `comments`: `floor` int => [`comment body`](#comment_body)

评论

## music_body

> `pic`: image

图片

> `title`: string

歌曲名

> `author`: string

作者

> `music`: file

音乐

## comment_body

> `poster`: int = `user.id`

发布用户

> `reply`: int = `comments.floor`

回复楼层

> `datetime`: time

发布时间

> `text`: string

评论内容