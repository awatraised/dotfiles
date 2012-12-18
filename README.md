USAGE
=====

~/.bash_profile

`DOTFILES=$HOME/.dotfiles

alias ls='ls -h'
alias l='ls'

if [[ -s $DOTFILES/aliases ]] ; then source $DOTFILES/aliases ; fi
if [[ -s $DOTFILES/functions ]] ; then source $DOTFILES/functions ; fi`
