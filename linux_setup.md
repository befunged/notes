# Linux Setup

## fonts-powerline
- wsl
  - install in windows using https://slmeng.medium.com/how-to-install-powerline-fonts-in-windows-b2eedecace58 
  - change font in windows terminal)
- linux
  - apt install fonts-powerline

## Zellij - terminal multiplexer
- download from https://github.com/zellij-org/zellij/releases
- untar and copy to /usr/local/bin
- echo 'eval "$(zellij setup --generate-auto-start zsh)"' >> ~/.zshrc
- if mouse paste is broken, hold shift when right-click pasting
  


## Atuin - terminal history
- https://github.com/ellie/atuin
  - bash <(curl https://raw.githubusercontent.com/ellie/atuin/main/install.sh)
  - atuin import auto
  - echo 'eval "$(atuin init zsh)"' >> ~/.zshrc

## Fzf - fuzzy finder
-- apt install fzf


Tldr - command line help
bat - better than cat
Bpytop - better htop
Lf - file browser
LSD - ?
