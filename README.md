# Dotfiles

Misc. dotfile configurations, *excluding my Vim configs* which
[have their own repository][dotvim].

[dotvim]: https://github.com/flarnie/dotvim/commits?author=flarnie

## Setting Up

### Applications to set up

* Firefox
* Chrome (for testing)
* [Slate](https://github.com/jigish/slate)
  - [Use solution from recent issue to set up permissions.](https://github.com/jigish/slate/issues/528)
  - Navigate to Preferences > Security & Privacy > Privacy > Accessibility
  - Give Slate permission to control size/position of windows.
* [Homebrew](https://brew.sh/)
* iterm
  - `brew install iterm2`
* zsh
  - `brew install zsh`
* [oh-my-zsh](https://ohmyz.sh/)
* [Solarized for iterm2](https://github.com/altercation/solarized/tree/master/iterm2-colors-solarized)
  - Profiles > Edit Profiles > Preferences > Color Presets


### The Dotfiles

`git clone git@github.com:flarnie/dotfiles2.git ~/.dotfiles/`

`ln -s .dotfiles/.jshintrc .jshintrc`
`ln -s .dotfiles/slate ~/.slate`
`ln -s .dotfiles/git-commit-message ~/.gitmessage`
`git config commit.template ~/.gitmessage`

