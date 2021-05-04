# git-fancy-branch

[中文](./README_ZH.md)

If you are also in the following situations, probably you also need `git-fancy-branch`:

1. Prefer GIT command line rather than any GUI tools.
2. Always create new branches, and forget to delete them after branch merged.
3. Always working and switching across different branches, and something forget the branch name recently worked with.
4. Alway doing `git checkout`, and `TAB` for the target branches.

## Features

1. List all branches which sorted by commit time.
2. Using `fzf` to do fuzzy find across branches.
3. Support multiple branches delete.

![image](https://user-images.githubusercontent.com/2182004/116886592-d924c880-ac5b-11eb-9890-cc37afeb9fe9.png)


## Install

You can simply copy the script code to your executable directory, or you can use the following command to do this:

```
sudo wget https://raw.githubusercontent.com/Gcaufy/git-fancy-branch/main/git-br -O /usr/local/bin/git-br && sudo chmod +x /usr/local/bin/git-br
```

You also can use `npm` to install it:

```
npm install git-fancy-branch -g
```


## License
MIT
