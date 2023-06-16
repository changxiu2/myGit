# git

查看版本     git --version

### git是什么

集中式版本控制系统(vcs) => svn

分布式版本控制系统(dvcs) => git



### git作用

1.在项目开发的过程中，对值得记录的时间节点进行"备份"，方便后期恢复(后悔药)

2.方便团队协作开发

### git管理文件的三种状态

已修改（modified）：表示修改了文件，但还没保存到数据库中

已暂存（staged）：表示对一个已修改的文件的当前版本做了标记，使之包含在下次提交的快照中

已提交（committed）：表示数据已经安全地保存在本地数据库中



### 初次运行Git前的配置

配置用户名和邮箱
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com





```
git config --list
```



```js
git add . 将所有文件放到暂存区（经常做的）

git commit -m "提交信息" 将暂存区文件提交到仓库（某个功能完成的时候/在必要时候提交）

[工作区] ——git add .——> [暂存区] ——git commit -m "xxx"——> [仓库repo]

[工作区] ——git commit -a -m "xxx"——> [仓库repo](vim 编辑器操作)



git reset --soft commit_id
git reset --hard commit_id
git reset --mixed commit_id(默认) = git reset commit_id

HEAD:
HEAD^:
HEAD ~ n:


[工作区] <——git add .——> [暂存区] <——git commit -m "xxx"——> [仓库repo]
```



查看

```
git log
```

































