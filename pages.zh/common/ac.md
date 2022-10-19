# ac

> 打印用户连接时间的统计数据。
> 更多信息：<https://man.openbsd.org/ac>.

- 打印当前用户连接的时间，以小时为单位：

`ac`

- 打印用户连接的时间，以小时为单位：

`ac -p`

- 打印一个特定用户的连接时间，以小时为单位：

`ac -p {{用户名}}`

- 打印一个特定用户每天连接的时间，以小时为单位（包括总数）：

`ac -dp {{用户名}}`