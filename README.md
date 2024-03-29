# ck_notes
- 自己学习时记录的笔记
- 网上总结的笔记

-----------------------------------

git上传仓库代码：

```
git init 在本地计算机新建一个Git仓库
git remote add origin git@github.com:yourName/yourRepo.git 进入要上传本地的仓库，在本地路径中打开git bash，使用这个命令建立远程连接
git add 文件名
git commit -m "提交注释说明"
git push origin master .git push命令会将本地仓库推送到远程服务器。
```

要将多个文件一次性上传到 Git 仓库中，可以使用以下命令：

1. 将所有要上传的文件添加到 Git 仓库中。

```
git add <file1> <file2> <file3> ...
```

1. 提交所有更改到 Git 仓库中。

```
git commit -m "commit message"
```

在上面的命令中，`<file1> <file2> <file3> ...` 是要上传的文件名，可以使用空格分隔多个文件名。`<commit message>` 是提交时的注释信息。

1. 将更改推送到远程 Git 仓库中。

```
git push
```

这将会将所有更改推送到远程 Git 仓库中。

如果您要一次性上传一个目录中的所有文件，可以使用以下命令：

1. 将目录中的所有文件添加到 Git 仓库中。

```
git add <directory>/*
```

1. 提交所有更改到 Git 仓库中。

```
git commit -m "commit message"
```

在上面的命令中，`<directory>` 是要上传的目录名。

1. 将更改推送到远程 Git 仓库中。

```
perlCopy code
git push
```

这将会将目录中的所有文件推送到远程 Git 仓库中。
