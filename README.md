# Installation

     git clone https://github.com/arutinn/vim.git ~/.vim

     mkdir -p ~/.vim/autoload ~/.vim/bundle && \
     curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
     git clone https://github.com/scrooloose/nerdtree.git ~/.vim/bundle/nerdtree

     mkdir ~/.fonts
     cd ~/.fonts && curl -fLo DroidSansMonoForPowerlinePlusNerdFileTypes.otf https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/DroidSansMono/complete/Droid%20Sans%20Mono%20Nerd%20Font%20Complete%20Mono.otf?raw=true

     ln -s  ~/.vim/.vimrc ~/.vimrc
     sudo apt-get install ctags wmctrl

Open vim and run next command: `PlugInstall`

*Based on [galulex/vim](https://github.com/galulex/vim)*
