# dotfiles

## Path
### Tmux
- tmux.conf:`~/.tmux.conf`
### matplotlib
- matplotlibrc:`~/.config/matplotlib/matplotlibrc`
### vim

    ln -s vim ~/.vim
    ln -s ~/.vim/vimrc ~/.vimrc

syntax file:asy.vim ==> more info can be found in the asymptote manual.
colorscheme:
### Asymptote
- config.asy:`/usr/local/texlive/2015/texmf-dist/asymptote/config.asy`
### offlineimap
- offlineimaprc:`~/.offlineimaprc`
### ~/.bashrc
```
# enable fcitx in emacs of english linux
export GTK_IM_MODULE=fcitx
export XMODIFIERS=@im=fcitx

export LC_CTYPE=zh_CN.UTF-8


#TeXlive2016
export MANPATH=${MANPATH}:/usr/local/texlive/2016/texmf-dist/doc/man
export INFOPATH=${INFOPATH}/usr/local/texlive/2016/texmf-dist/doc/info
export PATH=${PATH}:/usr/local/texlive/2016/bin/i386-linux
```
