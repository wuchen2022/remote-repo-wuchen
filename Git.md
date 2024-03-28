Git是一个免费开源的分布式版本控制系统

https://git-scm.com/

版本控制系统

- 集中式

  SVN、CVS

- 分布式

  Git、Mercurial



Git的使用方式

- 命令行
- 图形化界面GUI
- IDE插件/扩展

## 配置git

![Snipaste_2024-03-28_22-51-54](C:\Users\Administrator\Desktop\Git\Snipaste_2024-03-28_22-51-54.PNG)

## 创建仓库

![Snipaste_2024-03-28_23-11-06](C:\Users\Administrator\Desktop\Git\Snipaste_2024-03-28_23-11-06.PNG)

文件状态

![Snipaste_2024-03-28_23-12-08](C:\Users\Administrator\Desktop\Git\Snipaste_2024-03-28_23-12-08.PNG)



鼠标右键>Git Bash Here

git init 创建仓库

~~~git
git init <project-name>
创建一个新的本地仓库 （省略project-name则在当前目录创建。）
~~~

git status 查看仓库的状态

git add 添加到暂存区

~~~git
git add *
git add 文件名
~~~

git commit 提交

~~~git
git commit -m "提交信息"
~~~

只会提交暂存区文件

git reset -- 参数

- soft 工作区和暂存区内容都**不会**被清空
- hard 工作区和暂存区内容都**会**被清空
- HEAD

git ls-files 查看暂存区

ls 查看工作区

![Snipaste_2024-03-28_23-15-22](C:\Users\Administrator\Desktop\Git\Snipaste_2024-03-28_23-15-22.PNG)

git logo 查看提交历史

~~~git
git log --oneline
~~~

git reflog 查看操作历史记录



git diff

查看工作区，暂存区，本地仓库直接的差异



## 远程仓库

GitHub

代码托管平台，超过90%的开源项目都托管在github上

https://github.com/

|        | 用户名     |      | 密码   |      |                   |
| -----: | ---------- | ---- | ------ | ---- | ----------------- |
| github | wuchen2022 |      | ****** |      | 1036542915@qq.com |

创建ssh密钥

~~~git
cd ~/.ssh
ssh-keygen -t rsa -b 4096
密钥文件名 id_rsa
密钥文件密码:******

ls -ltr
C:\Users\Administrator\.ssh\id_rsa 私钥文件
C:\Users\Administrator\.ssh\id_rsa.pub 公钥文件 
~~~





