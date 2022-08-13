Apptemt to remember what I did

Install
sudo pacman -Syu
sudo pacman -S conky rofi ranger vim neofetch tmux zsh base-devel w3m git htop btop zsh-syntax-highlighting zsh-autosuggestions

Font
sudo cp -r ~/Downloads/Dotfiles/fonts/Hack /usr/share/fonts
sudo cp -r ~/Downloads/Dotfiles/fonts/Iosevka /usr/share/fonts
fc-list -f -v

Theme
sudo cp -r ~/Downloads/Dotfiles/themes/Nordic-Blue /usr/share/themes
sudo cp -r ~/Downloads/Dotfiles/themes/ZorinBlue-Dark /usr/share/themes

Icon
sudo cp -r ~/Downloads/Dotfiles/icons/Borealis-cursors /usr/share/icons
sudo cp -r ~/Downloads/Dotfiles/icons/Tela-circle /usr/share/icons
sudo cp -r ~/Downloads/Dotfiles/icons/Tela-circle-dark /usr/share/icons
sudo cp -r ~/Downloads/Dotfiles/icons/Zafiro-Icons-Dark-Blue /usr/share/icons

Ranger
cp ~/Downloads/Dotfiles/ranger/* ~/.config/ranger/

Rofi(super+/ or alt+/)
touch ~/.local/share/rofi/themes/
touch ~/.config/rofi
cp ~/Downloads/Dotfiles/rofi/better-nord.rasi  ~/.local/share/rofi/themes/
cp ~/Downloads/Dotfiles/rofi/config.rasi ~/.config/rofi/
cp ~/Downloads/Dotfiles/rofi/rofi-power-menu ~/.config/rofi/rofi-power-menu

rofi -show power-menu -modi power-menu:~/.config/rofi/rofi-power-menu
rofi -show drun

Tmux
https://github.com/tmux-plugins/tpm
cp tmux ~/.config/
cp .tmux.conf ~/

Vim
cp -r ~/Downloads/Dotfiles/vim ~/
cp ~/Downloads/Dotfiles/.vimrc ~/

Wallpaper
cp -r ~/Downloads/Dotfiles/wallpapers/ ~/Pictures

Xfce terminal
touch ~/.config/xfce4/terminal/colorschemes
cp ~/Downloads/Dotfiles/xfce-theme/nord.theme ~/.config/xfce4/terminal/colorschemes

Zsh
cp -r ~/Downloads/Dotfiles/zsh/ ~/
cp ~/Downloads/Dotfiles/.zshrc ~/

Conky
cp ~/Downloads/Dotfiles/conky/ ~/

Keyboards
Super T FileManager
Super M MailReader
Super N WebBrowser

Super+Return xfce4-terminal
Ctrtl+super+return dropdown

Window
Alt+Q kill
Qlt+W close
Alt + 1 WS1
Alt + 2 WS2
Alt + 3 WS3
Alt + 4 WS4

Alt + Up maximum
Alt + Left split left
Alt + Right split right
Alt +Shift+Up Move window
Alt+ Shift + Down Resize window
Alt + Shift + Left -> WS
Alt + Shift + Right <- WS

Cycle window ALt-Tab
Cycle window(Reverse) ALt-Shift-Tab


Alt + S stick window
Alt + D hide all windows

Small window adjustments
Window manager
Advanced 
wrap WS off

Lastly
sudo pacman -S thunderbird libreoffice gimp kdenlive obs-studio discord

Somefix
Nivida driver EOS
https://discovery.endeavouros.com/nvidia/nvidia-installer/2021/03/

Nivida driver Manjaro
sudo mhwd -a pci nonfree 0300
https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-manjaro-linux

Fix backlight in EOS/Manjaro
https://forum.endeavouros.com/t/systemd-backlight-service-failed/11783/6
https://forum.manjaro.org/t/cant-adjust-screen-brightness-lenovo-laptop-nvidia-xfce/28771/14

Stickey
https://forum.endeavouros.com/t/systemd-backlight-service-failed/11783/6




