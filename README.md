# termux
### Before doing anything after fresh install, otherwise apt and pkg won't even work
```
apt upgrade
termux-setup-storage
```
```
pkg install git
pkg install zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
chsh -s zsh
cd $HOME
git clone https://github.com/adi1090x/termux-style
cd termux-style
./install
```
