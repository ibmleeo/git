# GIT 操作

| 命令                                | **说明**                          |
| --------------------------------- | ------------------------------- |
| git config --global user.name 用户名 | 设置用户签名                          |
| git config --global user.email 邮箱 | 设置用户签名                          |
| git init                          | 初始化本地库                          |
| git status                        | 查看本地库                           |
| git config -list                  | 查看git配置信息                       |
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

## 1. git安装

### 1.1 Homebrew

```shell
Install [homebrew](https://brew.sh/) if you don't already have it, then:  
`$ brew install git`

if not install homebrew,then input below command to install homebrew:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

```

### 1.2 MacPorts

```shell
Install [MacPorts](https://www.macports.org) if you don't already have it, then:  
`$ sudo port install git`
```

### 1.3 Xcode

```shell
Apple ships a binary package of Git with [Xcode](https://developer.apple.com/xcode/).
```



## 2. 配置用户名和邮箱.

```shell
git config --global user.name 用户名 (用于本地库记录版本信息)

git config --global user.email 邮箱

```

## 3. 创建和上传ssh公钥

### 3.1创建公钥

```shell
ssh-keygen -t rsa -C liyong0610  ----一般保存在～/.ssh/id_rsa.pub
```

### 3.2 上传公钥到github

## 4. 初始化本地库

```shell
先创建一个作为本地库的文件夹，然后在该目录
git init  
```

## 5. 连接远程库

```shell
创建远程库别名：
git remote add 别名 远程库地址
```

## 6 . 本地库操作

```shell
git add 文件名  ---添加文件到暂存区
git commit -m "日志信息" 文件名。----提交到本地库
git reflog  --- 查看历史版本记录，可查看各版本的版本号
git reset --hard 版本号   --- 版本穿梭
git rm --cache 文件名  --- 删除暂存区的文件
git status  ----- 查看本地库的信息

```



- 
