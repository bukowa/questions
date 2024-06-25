
1. How to make ZSH the default shell?
```shell
chsh -s $(which zsh)
```
2. How can I view all shell scripts executed when /bin/sh starts ?
```shell
/bin/sh -lixc exit 2>&1
```
