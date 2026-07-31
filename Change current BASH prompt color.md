# Change current BASH prompt color
```sh
vi ~/.bashrc
export PS1="\[\e[36m\]\u@\h\[\e[0m\]:\[\e[33m\]\W\[\e[0m\]\$ "
```
MySQL Prompt.
```sh
export MYSQL_PS1='\u@mysql [\d]> '
# user@mysql [dbname]>
```
