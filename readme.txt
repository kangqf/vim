git clone https://github.com/kangqf/vim.git ~/


git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

git clone https://github.com/Valloric/YouCompleteMe.git ~/.vim/bundle/YouCompleteMe --depth 1

cd ~/.vim/bundle/YouCompleteMe
  ./install.sh
   git submodule update --init --recursive

vim :PluginInstall

mv ./kqfsnippets ~/.vim/bundle/ultisnips/
