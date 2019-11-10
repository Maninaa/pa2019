# About this repository

This is the repository for *PA 2019 Fall* (version 3.2) in Nanjing University.

Please follow the steps in the chapter *PA 0* of the guide (under the `docs` directory in this project) to start.

You can find the guide at:

http://114.212.80.187/wl/pa2019_fall_guide/blob/master/PA_2019_fall_Guide.pdf

# Discussion

Goto the following link for technical issues. DO NOT discuss in the QQ group, no answer will be provided there.

http://114.212.80.187/wl/pa2019_fall/issues

# About this Gitlab server

This server is scheduled to reboot every day at 5am, and backup every sunday at 1am. 

DO NOT try to pull or push around this time.

# 如何迁移到新服务器

新服务器IP地址：114.212.10.212

在本地执行如下步骤：

1. 删除文件`~/.ssh/known_hosts`
2. 使用`git remote -v`命令查看当前地址
3. 使用`git remote set-url origin ssh://git@114.212.10.212:8022/xxx`设置新的仓库地址
    * 其中`xxx`为通过第2步的`git remote -v`命令所获取的用户名和仓库名
    * 如果是`http`协议的用户，使用`git remote set-url origin http://114.212.10.212/xxx`命令进行设置