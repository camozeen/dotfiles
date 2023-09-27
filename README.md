# About

dot files/dirs in home

## dot-vim

clone vim-plug into `.vim` directory

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

make a directory `swapfiles` in `.vim`

```
mkdir ~/.vim/swapfiles
```

copy `.vimrc`

```
cp ./dot-vim/vimrc ~/.vimrc
```
