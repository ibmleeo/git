# GIT 操作：

| 命令                                | **说明**                          |
| --------------------------------- | ------------------------------- |
| git config --global user.name 用户名 | 设置用户签名                          |
| git config --global user.email 邮箱 | 设置用户签名                          |
| git init                          | 初始化本地库                          |
| git status                        | 查看本地库                           |
| git add 文件名                       | 添加到暂存区                          |
| git commit -m "日志信息" 文件名          | 提交到本地库                          |
| git reflog                        | 查看历史记录                          |
| git rm --cache 文件名                | 删除暂存 区的文件                       |
| git reset --hard 版本号              | 版本穿梭                            |
| git branch 分支名                    | 创建分支                            |
| git branch -v                     | 查看分支                            |
| git checkout 分支名                  | 切换分支                            |
| git merge 分支                      | 把制定的分支合并到当前分支                   |
| git remote -v                     | 查看远程库                           |
| git remote add 别名 远程地址            | 创建远程库别名                         |
| git push 远程库 分支名                  | 推送本地库到远程库                       |
| git pull 远程库 分支名                  | 拉扯远程库到本地库                       |
| git clone 远程库                     | 克隆远程库                           |
| ssh-keygen -t rsa -C liyong0610   | 创建公钥(mac 保存在： ～/.ssh/id_rsa.pub |
|                                   |                                 |

- 设置用户签名

```shell
git config --global user.name 用户名
git config --global user.email 邮箱
```

- 初始化本地库

```shell
git init
```

- 查看本地库

```shell
git status
```

- 添加到暂存区

```shell
git add 文件名
```

- 提交到本地库

```shell
git commit -m "日志信息" 文件名
```

- 查看历史记录

```shell
git reflog
```
