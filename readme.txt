git clone https://github.com/kangqf/vim.git ~/


git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

git clone https://github.com/Valloric/YouCompleteMe.git ~/.vim/bundle/YouCompleteMe --depth 1

cd ~/.vim/bundle/YouCompleteMe
  ./install.sh
   git submodule update --init --recursive
   
sudo apt-get install ctags

vim :PluginInstall

mv ./kqfsnippets ~/.vim/bundle/ultisnips/

cd /usr/include/c++/4.8
ctags -R --c++-kinds=+l+x+p --fields=+iaSl --extra=+q --language-force=c++ -f stdcpp.tags


some tips

1. make sure you have the same project defined in index config file.
