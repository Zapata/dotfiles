dotfiles
============

Configuration files for Linux setup.
Work also with Bash on Windows.

```sh
cd $HOME
git clone https://github.com/Zapata/dotfiles.git 
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.vimrc .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```
