# MakeVimAwesome
Make Vim like Visual Studio
## Install Vim
```
$ sudo apt-get install vim
            OR
$ sudo yum install vim
```

## Install vim in Linux 
```
$ sudo yum install wget
$ bash -c "$(wget -q -O - https://linux.kite.com/dls/linux/current)"
```
Kite automatically integrates with all the text editor available. To integrate it manually with vim follow the steps

## Integrate Vim and Kite
```
$ mkdir -p ~/.vim/pack/kite/start/kite
$ mkdir clone https://github.com/kiteco/vim-plugin.git ~/.vim/pack/kite/start/kite/
```
Restart Vim

## download vim-plug
```
$ sudo yum install curl
$ curl -fLo ~/.vim/autoload/plug.vim/ --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
## Install Puggins
Run the command in .vimrc
```
$ source %
$ :PlugInstall
```

## Contribute
Raise an issue and create a pull request on the issue.
