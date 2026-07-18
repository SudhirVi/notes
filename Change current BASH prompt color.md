# Change current BASH prompt color
```sh
vi ~/.bashrc
export PS1='\[\e[0;33m\]\u@\h \[\e[1;34m\]\W\[\e[0;33m\]\$\[\e[0m\] '
#export PS1="\[\e[31m\][\[\e[m\]\[\e[38;5;172m\]\u\[\e[m\]@\[\e[38;5;153m\]\h\[\e[m\] \[\e[38;5;214m\]\W\[\e[m\]\[\e[31m\]]\[\e[m\]\\$ "
# export PS1="\[\e[38;5;253m\][\[\e[38;5;28m\]\u\[\e[38;5;34m\]@\h \[\e[38;5;40m\]\W\[\e[38;5;253m\]]\[\e[0m\]\$ "
# export PS1="[\\u@\\h \\W]❯🐧 "
```
MySQL Prompt.
```sh
export MYSQL_PS1=$'\e[1;36m\\u@\\h\e[0m \e[1;32m[\\d]\e[0m> '
```
