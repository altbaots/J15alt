auto-green
Build Status

自动保持 GitHub 提交状态常绿。

a commit a day keeps your girlfriend away.

原理
使用 GitHub Actions 的定时任务功能，每隔一段时间自动执行 git commit，提交信息为 "a commit a day keeps your girlfriend away"，灵感来自知乎问题在 GitHub 上保持 365 天全绿是怎样一种体验？下某匿名用户的回答：

曾经保持了 200 多天全绿，但是冷落了女朋友，一直绿到现在。

有关 Github Action 的原理，可查看官方文档 Github Action 简介

使用
点右上角 Use this template 按钮复制本 GitHub 仓库，⚠️ 千万不要 Fork，因为 fork 项目的动态并不会让你变绿 ⚠️
修改 ci.yml 文件的第 7、8 行 去掉前面的 # 号
修改 ci.yml 文件的第 23 行 为自己的 GitHub 邮箱账号
(可选) 你可以通过修改 ci.yml 文件的第 8 行来调整频率
计划任务语法有 5 个字段，中间用空格分隔，每个字段代表一个时间单位。
