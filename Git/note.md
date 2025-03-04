## 1.初始化当前文件夹，可以开始进行git操作

```bash
git init
```

## 2.将文件加入暂存区

```bash
git add <file1> <file2> <file3> # 可以一次性添加多个文件
git add . # 将当前文件夹所有文件添加到暂存区
git add -p # 分段添加一个文件的不同内容，git会区分出一个文件中不同部分的变更
```

## 3.查看当前状态

```bash
git status
```

## 4.提交当前暂存区并保存

```bash
git commit -m "<message>"
```

## 5.显示工作目录与暂存区的差异

```bash
git diff
git diff --cached # 暂存区与最近一次提交的差异
```

## 6.查看提交日志

```bash
git log
```

## 7.将文件从暂存区还原至工作区

```bash
git restore "<file>"
```

## 8.将文件从最后一次提交还原至暂存区

```bash
git restore --staged "<file>"
```

## 9.若文件最后一次提交存在纰漏，则将最后一次提交的版本更换为当前暂存区

```bash
git commit --amend "<file>"
```

## 10.将代码仓库推送至GitHub

```bash
git remote add origin url # 往当前文件夹添加远程仓库，仓库名为origin
git remote set-url origin NEW_URL # 设置某个远程仓库的地址
git remote remove origin # 删除远程仓库
git push -u origin master # 将master分支的历史推送origin，加入参数-u则在推送的同时绑定master与origin
```



### 首次push时对公私钥的配置

```bash
ssh-key # 创建公私钥
# 配置完成后在相关文件中找到公钥添加到github
```

