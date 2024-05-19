# Dotfiles

Misc. dotfile configurations, _excluding my Vim configs_ which
[have their own repository][dotvim].

[dotvim]: https://github.com/flarnie/dotvim/commits?author=flarnie

## Setting Up

### Applications to set up

- Firefox

- Chrome (for testing)

- Making a `Code` directory and favoriting it.

  - Open the Finder Window.
  - Click on "File" -> "Find".
  - In the top right search textfield, enter the folder name you want to link to.
  - In the dropdown menu, filter by "Folder".
  - Once you find the folder, drag and drop it in the Favorites.

- [Rectangle App](https://rectangleapp.com/)
- [Homebrew](https://brew.sh/)

- iterm

  - `brew install iterm2`

- zsh

  - `brew install zsh`

- [oh-my-zsh](https://ohmyz.sh/)

- [Solarized for iterm2](https://github.com/altercation/solarized/tree/master/iterm2-colors-solarized)

  - Profiles > Edit Profiles > Preferences > Color Presets

- VSCode and extensions
  - [Apollo GraphQL for VSCode](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo)
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  - [Language Support for Java(TM) by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
  - [Prettier - Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
  - [VSCode Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
  - [Visual Studio Intellicode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
  - [Vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)
  - [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
  - [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
  - [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

### The Dotfiles

`git clone git@github.com:flarnie/dotfiles2.git ~/.dotfiles/`

`ln -s .dotfiles/slate ~/.slate`

`ln -s .dotfiles/git-commit-message ~/.gitmessage`

`git config --global commit.template ~/.gitmessage`

Set the configs in VSCode by copy-pasting.
Open Preferences > Settings, and click the button in the top right.
[The button in the top right once you open preferences > settings](how_to_set_vscode_configs.png)
