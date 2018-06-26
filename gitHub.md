### gitHub
* 注册登录
* git版本查看 `git --version`
* 下载git [git下载地址](https://git-scm.com/downloads)
* 更新git `git clone https://github.com/git/git  `
* 生成SSH Key

**在Linux和Mac系统中都自动安装了SSH，Windows系统需要安装Git Bash。**

首先检查下本机是否已经安装了SSH，在终端输入ssh即可：
接下来就是生成ssh key了，输入`ssh-keygen -t rsa`，然后连续按回车键三次

* 查看本地的key


```
cd ~/.ssh
cat id_rsa.pub
```
* 测试SSH Key成功
`ssh -T git@github.com`

##注意：
`Repository name`: 仓库名称

`Description(可选)`: 仓库描述介绍

`Public, Private `: 仓库权限（公开共享，私有或指定合作者）

`Initialize this repository with a README`: 添加一个README.md

`gitignore`: 不需要进行版本管理的仓库类型，对应生成文件.gitignore

`license`: 证书类型，对应生成文件LICENSE22
