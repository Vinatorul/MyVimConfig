### Hello, this is my vim config

Make sure that you backup your own .vimrc
```bash
mv ~/.vimrc ~/backup.vimrc
```
Then clone this repo and replace config
```bash
$ git clone https://github.com/Vinatorul/MyVimConfig.git && cd MyVimConfig  # clone repo
$ mv .vimrc ~/.vimrc -i                                                     # move .vimrc
$ cd .. && rm -rf MyVimConfig                                               # delete repo
```
You will also need to install [Vundle](https://github.com/VundleVim/Vundle.vim) and then install all plugins
```vim
:PluginInstall
```
Plugin [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) also need a special installation after runnig Vundle install
```bash
cd ~/.vim/bundle/YouCompleteMe
./install.py --racer-completer
```
