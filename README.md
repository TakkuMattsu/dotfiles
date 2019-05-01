dotfiles
========

My personal configuration

Install
--------

```bash
 $ git clone git://github.com/TakkuMattsu/dotfiles.git ~/dotfiles
```


Setup
--------

```bash
 $ cd ~/dotfiles
 $ ./setup.sh
 $ brew bundle
```
This script create a symbolic link as following:

* .vim              -> vimfiles
* .vimrc            -> dotfiles/.vimrc
* .screenrc         -> dotfiles/.screenrc
* .tmux.conf        -> dotfiles/.tmux.conf
* .bashrc           -> dotfiles/.bashrc
* .bash_profile     -> dotfiles/.bash_profile
* .dein.toml        -> dotfiles/.dein.toml
* .dein_lazy.toml   -> dotfiles/.dein_lazy.toml
* .tigrc            -> dotfiles/.tigrc
* .tmux-powerlinerc -> dotfiles/.tmux-powerlinerc 
* .inputrc          -> dotfiles/.inputrc
