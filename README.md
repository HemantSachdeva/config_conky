# Conky
Package name
>conky-lua-nv

# Installation
On Arch, Manjaro, Garuda or any other Arch based Linux Distro
>sudo pacman -Qi conky-lua-nv

(You can google the installation steps if you are on any other Linux like Ubuntu, Fedora etc..etc..)

# Set-up
1. Clone my repository or download it zip file and extract it.
2. Now check if ~/.config/conky/ directory exists(if doesn't then create one) and copy both 
```conky.conf``` and ```conky.lua``` file in the direcory.
3. You can also place both the files in home directory but then you have to rename ```conky.conf``` to ```.conckyrc``` by following cmd
>mv /path/to/conky.conf ~/.conkyrc

You need to change value of ```lua_load``` variable to the new path of conky.lua (only if you are not placing conky.lua in ```~/.config/conky/conky.lua```) in ```.conkyrc```.
To use more than one ```conky.conf``` or ```.conkyrc``` config files use
>conky -c path/to/conky.conf

# Output of above config file
![img](https://i.imgur.com/wEufDWn.png)
![img](https://i.imgur.com/quxKeaO.png)

>Found at
https://github.com/brndnmtthws/conky/wiki/Configs