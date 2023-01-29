# Linux Setup

## zsh
- `apt install zsh wget git`
- `sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"`

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
`cd **<TAB>`

## Tldr - better command line help
- `apt install tldr`
  
## bat - better than cat
- `apt install bat`
- `alias bat='batcat`

## Bpytop - better htop
- `pip3 install bpytop --upgrade`
- 

## lf - file browser

## lsd - better than ls
  
