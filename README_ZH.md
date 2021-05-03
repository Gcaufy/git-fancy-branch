# git-fancy-branch

[中文](./README_ZH.md)


如果你满足以下条件，那么大概率你也需要 `git-fancy-branch`:

1. 习惯用 Git 命令行而不是 GUI 工具。
2. 经常创建新的分支，并且在合并后忘关闭导致本地分支泛滥。
3. 经常来回切换分支，但有的时候忘记了之前是在哪个分支工作。
4. 经常在做 `git checkout` 时，多次使用 `TAB` 键便于找到目标分支。


## 特性

1. 分支列表以最近提交排序，方便快速定位到最近的工作分支。
2. 使用 `fzf` 进行快速分支选择。
3. 支持批量选择分支进行删除。

![image](https://user-images.githubusercontent.com/2182004/116886592-d924c880-ac5b-11eb-9890-cc37afeb9fe9.png)


## 安装

可直接拷贝脚本源码至可执行目录

```
sudo wget https://raw.githubusercontent.com/Gcaufy/git-fancy-branch/main/git-br -O /usr/local/bin/git-br && sudo chmod +x /usr/local/bin/git-br
```

也可以使用 `npm` 安装：

```
npm install git-fancy-branch -g
```


## License
MIT
