sudo pacman -S --needed base-devel git



git clone https://aur.archlinux.org/yay.git


cd yay


makepkg -si


conf --gen > ~/.config/aura/config.toml

yay --version

yay -S coolercontrol


sudo systemctl enable --now coolercontrold
