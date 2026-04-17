#
# ~/.bashrc
#

# If not running interactively, don't do anything
[[ $- != *i* ]] && return

alias ls='ls --color=auto'
alias grep='grep --color=auto'
PS1='[\u@\h \W]\$ '
set -o vi
source <(kubectl completion bash)
alias k=kubectl
complete -o default -F __start_kubectl k

eval "$(starship init bash)"
