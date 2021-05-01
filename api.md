# 前言
这里是HajeeknのAPI,搭建在Vercel上,通过Python写

此代码已经完全开源: https://github.com/slblog-github/allapis

此API源于[冰老师](https://github.com/zfour/)

# 使用

## GitHub Actions 触发

触发地址: <https://all.api.slqwq.cn/api/v1/webhook>

参数:

| 参数 | 参数用途 |
| --- | --- |
| `user` | 你的 GitHub URL 账户名 |
| `source` | 你需要触发 GitHub Actions 构建的仓库 |
| `token` | GitHub Token 用于鉴权,否则无法触发 |

参数类型: string

## GitHub 贡献榜

触发地址: <https://all.api.slqwq.cn/api/v1/calendar>

参数:

| 参数 | 参数用途 |
| --- | --- |
| `user` | 你的 GitHub URL 账户名 |

参数类型: string

## 适用于小康友链的友链json展示

触发地址: <https://all.api.slqwq.cn/api/v1/link_json>

参数:

| 参数 | 参数用途 |
| --- | --- |
| `user` | 你的 GitHub URL 账户名 |
| `repo` | 你的运行小康友链爬虫的仓库 |
| `branch` | 爬虫存储friendslist.json的分支 |


