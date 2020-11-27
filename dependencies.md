# Dependencies

## Git
- `sudo apt install git`
- `ssh-keygen -t rsa -b 4096 -C "otar.zakalashvili@gmail.com" -N "" -f "$HOME/.ssh/id_rsa"`
- `sudo apt-get install xclip`
- `xclip -sel clip < ~/.ssh/id_rsa.pub`
- Add new SSH key to Github: https://github.com/settings/ssh/new

## Utilities
- `sudo apt install curl`
- `sudo apt-get install php7.4-fpm` // check latest version
- `sudo apt install gnome-tweaks`
- `sudo apt-get install -y dconf-editor`
### Indicator Souns Switcher
- `sudo apt-add-repository ppa:yktooo/ppa`
- `sudo apt update && sudo apt install indicator-sound-switcher` 


## Docker
https://docs.docker.com/engine/install/ubuntu/
https://docs.docker.com/compose/install/

## Dotfiles
- `cd ~ && git init && git remote add origin git@github.com:otarza/dotfiles.git && git fetch`

## ZSH
- `sudo apt install zsh`
- `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
- `source .zshrc`

## NVM
- `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash` // Check latest version
- `nvm install node`

## VIM
- `sudo apt install vim`
- `sudo apt-get install silversearcher-ag`
- `sudo apt-get install ripgrep`

