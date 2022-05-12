# scoir-zsh-functions
A collection of zsh functions to make my life easier working on code

##Installation

Copy the following into your ~/.zshrc file.
```
export ZSH_FUNCTION_ROOT=<path to this repository>
fpath=( $ZSH_FUNCTION_ROOT/**/*(F) "${fpath[@]}" )
autoload -Uz $ZSH_FUNCTION_ROOT/scoir-zsh/**/*(.:t)
```