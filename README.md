
install gnome nethunter 

sudo apt update && sudo apt upgrade -y
 
sudo apt install kali-desktop-gnome -y

Choose above 

nano .vnc/xstartup
Then get out and don't forget to put # in an old desktop


export XDG_CURRENT_DESKTOP="GNOME"
sudo service dbus start
gnome-shell --x11

If you encounter an error vncserver Put this code  
export XDG_CURRENT_DESKTOP="GNOME"


sudo service dbus start


gnome-shell --x11

Happy gnome (: 

# Gnome-nethunter-
