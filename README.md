# git-demo

## 配置

``` bash

git config --global user.name '名称'

git config --global user.email '邮箱'

```

## 密钥SSH key生成

``` bash

$ ssh-keygen -t rsa -C '邮箱'

```

## 基本操作

``` bash

git init 初始化仓库

git add <文件名>

git status 查看状态

git rm --cached <文件名> 删除文件

git add *.html 添加某一类的文件

git add .  添加所有文件

git commit 提交 使用i 然后输入内容  再按esc 接着:q或:q!退出

git commit -m '备注'   简写

忽略文件: 在根目录创建一个.gitignore文件

创建分支 git branch dev

切换分支 git checkout dev

合并分支 回到主线 git checkout master  然后git merge login

```
## github创建一个远程仓库

``` bash

git remote 查看是否连接远程库origin

git remote add origin 远程仓库地址

git push -u origin master 第一次push

克隆 git clone 远程仓库地址

拉取 git pull

推送 git push

```

## 特殊仓库(可做服务器) 如 名称.github.io

``` bash

# 使用自己域名：

1、根目录需要创建 CNAME 文件，内容： www.域名.com

2、域名解析（阿里云）

CNAME www 默认 名称.github.io(记录值)

CNAME @ 默认 名称.github.io(记录值)

```