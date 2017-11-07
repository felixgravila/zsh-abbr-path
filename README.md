# `theme_title_use_abbreviated_path equivalent` for zsh on osx

Couldn't find anything that worked for me so I made my own

## Installation
copy .abbr_pwd to $HOME then source it from your .zshrc
```
source $HOME/.abbr_pwd
```
You can use my own version if agnoster suits you, but if not you can edit your theme of choice in $HOME/.oh-my-zsh/themes by finding the prompt_dir() method and replacing the default to contain $(felix_pwd_abbr) as you wish. For agnoster it was as easy as replacing '%~' with $(felix_pwd_abbr).