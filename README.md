hello-worlds
============

The inital system setup for the hello worlds repos 

### XCode + CLI
Install XCode; Command line tools
     xcode-select --install

### Homebrew
     ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"


### ZSH
     brew install zsh

Hrmmm:

     curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
- Skip this, it's easy enough to follow the directions in their GH readme.md

### Configuring Git
     brew install git
     git config --global user.email you@example.com

Do you have two-factor authentication on?

1. Create a new access token (https://github.com/settings/applications)
2. Use token instead of password.


### My Dotfiles 
Clone dotfiles

     git clone xxx
     cd vim/vim/bundle
     git clone https://github.com/scrooloose/nerdtree.git

     ln -s ~/projects/dotfiles/vim/vimrc .vimrc
     ln -s ~/projects/dotfiles/vim/vim .vim

(or whereever your dotfiles are)

Don't forget to add ~/vim_swap! 

     mkdir ~/vim_swap
     
