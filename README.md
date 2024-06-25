
1. How to make ZSH the default shell?
```shell
chsh -s $(which zsh)
```
2. How can I view all shell scripts executed when /bin/sh starts ?
```shell
/bin/sh -lixc exit 2>&1
```
3. How can i view all files that shell sources when it starts?
```shell
/bin/bash -lixc exit 2>&1 | sed -n 's/^+* \(source\|\.\) //p'
```
