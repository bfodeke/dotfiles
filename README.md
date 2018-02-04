## There's no place like ~/

These are my dotfiles. I started mine as a fork of [shrop's dotfiles](https://github.com/shrop/dotfiles), which started as a fork of [pengwynn's dotfiles](https://github.com/pengwynn/dotfiles)

Dependencies to install via Homebrew, apt, or from source

* [git](https://git-scm.com)
* [Liquid Prompt](https://github.com/nojhan/liquidprompt)
* [The Silver Searcher](https://github.com/ggreer/the_silver_searcher)
* [Sack](https://github.com/sampson-chen/sack)
* [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh)
* [PHP CLI](http://php.net)
* [tmux](https://tmux.github.io)
* [Vim](http://www.vim.org)


### Installation
* `git clone https://github.com/bfodeke/dotfiles.git ~/.dotfiles`
* `cd ~/.dotfiles`
* `script/bootstrap`

The install script will symlink the appropriate files in .dotfiles to your home directory. Everything is configured and tweaked within ~/.dotfiles, though. All files and folders ending in .symlink get, you guessed it, symlinked. For example: ~/.dotfiles/vim/vimrc.symlink gets symlinked to ~/.vimrc.
