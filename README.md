# BuildMyVim
Use zsh,oh my zsh macvim,tmux ...
＃1.安装homebrew 
登陆网站 http://brew.sh/index_zh-cn.html
复制命令到命令行执行 /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

又提示缺少套件啦？别担心，Homebrew 随时守候。
＃2.安装zsh 
brew install zsh
＃3.安装oh my zsh sh 
-c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
＃4.安装macvim 
brew install macvim
#5. git 
clone https://github.com/datamaning/BuildMyVim.git
#6. mv .vimrc ~
#7 vim .vimrc & :PluginInstall

#end：
$ brew install wget
Homebrew 会将套件安装到独立目录，并将文件软链接至 /usr/local 。

Homebrew 会将套件安装到独立目录，并将文件软链接至 /usr/local 。
$ cd /usr/local
$ find Cellar
Cellar/wget/1.16.1
Cellar/wget/1.16.1/bin/wget
Cellar/wget/1.16.1/share/man/man1/wget.1

$ ls -l bin
bin/wget -> ../Cellar/wget/1.16.1/bin/wget
