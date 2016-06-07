VIM config
====

## vimrc file
将vimrc文件链接到*~/.vimrc*
```bash
test -e ~/.vimrc && /bin/mv -f ~/.vimrc{,.bak}
ln -s $PWD/vimrc ~/.vimrc
```

## vim folder
将vim目录链接到*~/.vim*
```bash
test -e ~/.vim && /bin/mv -f ~/.vim{,.bak}
ln -s $PWD/vim ~/.vim
```

## PlugInstall
```bash
vim
:PlugIntall
```
