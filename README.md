# zsh-config

**Setup**
- install zsh
  - sudo apt install zsh (or equivalent)
- set as default
  - chsh YOUR_USER (echo $USER)
  - /bin/zsh (verify location first)
- ensure git is isntalled
- backup any .zshrc that exists
  - mv ~/.zshrc ~/.zshrc.bak
- create new .zshrc
  - touch ~/.zshrc
- install font on system
  - sudo apt install ttf-jetbrains-mono-nerd (didn't work)
  - /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/JetBrains/JetBrainsMono/master/install_manual.sh)" gets from github, https://github.com/JetBrains/JetBrainsMono
    - also didn't really work? not sure what to do for wsl for now...
