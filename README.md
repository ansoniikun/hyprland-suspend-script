# hyprland-suspend-script

This is an automatic suspend script for hyprland using swayidle 

### Requirements
1. git
2. swayidle
3. nano/neovim/gedit

### Installation
Paste the following commands into your terminal:  
```
$ git clone https://github.com/ansoniikun/hyprland-suspend-script.git \
$ cd hyprland-suspend-script \
$ chmod +x suspend.sh \
$ mv suspend.sh ~/.config/hypr/scripts/
```


### Usage

1. `$ nano .config/hypr/hyprland.conf`

Paste into file:
`exec-once = ~/.config/hypr/scripts/suspend.sh # automatic suspend`

Ctrl + S to save  
Ctrl + X to exit
