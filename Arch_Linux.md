
// installing git
sudo pacman -S git


// installing bluetooth driver 
sudo pacman -S bluez
sudo pacman -S bluez-utils
sudo pacman -S blueman
sudo systemctl start bluetooth.service
sudo systemctl enable bluetooth.service
