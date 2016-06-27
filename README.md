## BuildMyVim
Use zsh,oh my zsh macvim,tmux ...
* 1.安装homebrew 
登陆网站 http://brew.sh/index_zh-cn.html
复制命令到命令行执行 /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
* 2.安装zsh 
brew install zsh
* 3.安装oh my zsh sh 
-c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
* 4.安装macvim 
brew install macvim
* 5.git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
* 6. git clone https://github.com/datamaning/BuildMyVim.git
* 7. mv datamaning/.vimrc ~
* 8. vim .vimrc & :PluginInstall

#end
* 1.brew install wget
* 2.Homebrew 会将套件安装到独立目录，并将文件软链接至 /usr/local 
* 3.cd /usr/local
* 4. find Cellar
* 5.Cellar/wget/1.16.1
* 6.Cellar/wget/1.16.1/bin/wget
* 7.Cellar/wget/1.16.1/share/man/man1/wget.1

* 8.ls -l bin
* 9.bin/wget -> ../Cellar/wget/1.16.1/bin/wget
