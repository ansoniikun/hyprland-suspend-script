# hyprland-suspend-script

This is an automatic suspend script for hyprland using swayidle 

### Requirements
1. git
2. swayidle
3. nano/neovim/gedit

### Installation
Paste the following commands into your terminal:
1. `$ git clone https://github.com/ansoniikun/hyprland-suspend-script.git`
2. `$ cd hyprland-suspend-script`
3. `$ chmod +x suspend.sh`
4. `$ mv suspend.sh ~/.config/hypr/scripts/`


### Usage

1. `$ nano .config/hypr/hyprland.conf`

Paste into file:
`exec-once = ~/.config/hypr/scripts/suspend.sh # automatic suspend`

Ctrl + S to save  
Ctrl + X to exit
