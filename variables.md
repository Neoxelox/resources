```sh
# ZSH
export ZSH=$HOME/.oh-my-zsh
ZSH_THEME="robbyrussell" # or "bira"

# GO
export PATH=$PATH:/usr/local/go/bin
export GOPATH=$HOME/go

# PYTHON
export PATH=$PATH:$HOME/.poetry/bin
export PYENV_ROOT=$HOME/.pyenv
export PATH=$PATH:$PYENV_ROOT/bin

# KUBERNETES
export KUBECONFIG=$KUBECONFIG:$HOME/.kube/sa-config

# RUBY
export GEM_HOME=$HOME/gems
export PATH=$PATH:$HOME/gems/bin

# BINS
export PATH=$PATH:/snap/bin

# ALIASES
alias cat=batcat
alias curl=curlie
alias python=python3
alias pip=pip3
alias c=clip.exe
alias gtree='git log --graph --abbrev-commit --decorate --date=relative --format=format:'\''%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)'\'' --all'

# PLUGINS
plugins=(git fzf)

# SHELL OVERRIDE
eval "$(pyenv init -)"
```
