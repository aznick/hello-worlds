hello-worlds
============

The inital system setup for the hello worlds repos 

### System Updates
(via App Store)

### XCode + CLI
Install XCode; Command line tools
     `xcode-select --install`

### Homebrew
     `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
     


### Update / Configure Git
     `brew install git`
[Generate / add new SSH Key](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)


### My Dotfiles 
Clone dotfiles

     git clone xxx
     cd vim/vim/bundle
     git clone https://github.com/scrooloose/nerdtree.git

     ln -s ~/projects/dotfiles/vim/vimrc ~/.vimrc
     ln -s ~/projects/dotfiles/vim/vim ~/.vim

(or whereever your dotfiles are)

Don't forget to add ~/vim_swap! 

     mkdir ~/vim_swap
     
Gcloud Command line tools
     
     curl https://sdk.cloud.google.com | bash
     gcloud auth login
