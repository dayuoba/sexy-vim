### Few Steps Setup A Sexy Vim

#### Preview

![](https://github.com/dayuoba/sexy-vim/blob/master/prevew.png)

Follow the below and you will get the sxy vim

* [oh-my-zsh](http://ohmyz.sh/)

install:
```
$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
* macvim with lua

install:
```
brew install macvim --with-cscope --with-lua --override-system-vim
brew linkapps macvim
```

* [source-code-pro](https://github.com/adobe-fonts/source-code-pro)
you can build the font your self or just download the ttf from this repository
then install it on your mac


* [Flat UI for terminal](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme)
download [Flat.terminal.zip]() and improt it from your terminal preference
then change the font to source-code-pro in settings 

* [spf13-vim](http://vim.spf13.com/) 

install:
```
curl http://j.mp/spf13-vim3 -L -o - | sh
```
* .vimrc.local for vim

here is an sample basic config 
```
set nonumber
set noexpandtab
set nospell
let g:indent_guides_enable_on_vim_startup = 0
colorscheme flattr
set listchars=tab:.\ ,eol:¬
```

All Done,Congratulations!Happy Hacking Now!
