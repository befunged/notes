# Linux Setup

## zsh
- `apt install zsh wget git vim vim-scripts curl python3 python3-venv`
- `sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"`
- vim .zshrc
  - update ZSH_THEME to "dpoggi"
  - append `export LS_COLORS=$LS_COLORS:'ow=1;34:'`
  - alias python='python3'
  - alias venvc='python3 -m venv .venv'
  - alias venva='source .venv/bin/activate'

## fonts-powerline
- wsl
  - install in windows using https://slmeng.medium.com/how-to-install-powerline-fonts-in-windows-b2eedecace58 
  - change font in windows terminal)
- linux
  - `apt install fonts-powerline`

## Zellij - terminal multiplexer
- download from https://github.com/zellij-org/zellij/releases
- untar and copy to /usr/local/bin
- `echo 'eval "$(zellij setup --generate-auto-start zsh)"' >> ~/.zshrc`
- if mouse paste is broken, hold shift when right-click pasting
  


## Atuin - terminal history
- https://github.com/ellie/atuin
  - `bash <(curl https://raw.githubusercontent.com/ellie/atuin/main/install.sh)`
  - `atuin import auto`
  - `echo 'eval "$(atuin init zsh)"' >> ~/.zshrc`
- cursor up shows history

## Fzf - fuzzy finder
- apt install fzf
- `cd **<TAB>` to try

## Tldr - better command line help
- `apt install tldr`
  
## bat - better than cat
- `apt install bat`
- `alias bat='batcat`

## Bpytop - better htop
- `apt install bpytop`

## lf - file browser
- apt install golang
- `env CGO_ENABLED=0 go install -ldflags="-s -w" github.com/gokcehan/lf@latest`

## lsd - better than ls
- download from https://github.com/Peltoche/lsd/releases
- `alias l='lsd -l'`
  
