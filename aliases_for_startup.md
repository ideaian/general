## These are aliases nice to put in my `~/.profile or ~/.bashrc` files. 

'''
bind '"\e[A":history-search-backward'
bind '"\e[B":history-search-forward'
alias dt="ls -ltr"
alias glh="git log | head -1 | cut -f2 -d' '"
alias glhc="glh | pbcopy"
alias pull="git pull; python setup.py develop"
alias dev="python setup.py develop"
alias nosetests="nosetests --logging-level=WARNING"
alias gp="git pull"
alias subl="/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl"
alias jpn="jupyter notebook"
alias gb="git branch"
alias gpush="git push"
alias gpull="git pull"
alias gf="git fetch"
alias gcam="git commit -am"
alias gs="git status"
alias gco="git checkout"
alias v="vim"
alias sl='ls'
```
