# gpu-passthrough-gtk
based off of gtk3 since the gtk4 version didnt have nice themes

not based off of https://github.com/uwzis/GPU-Passthrough-Manager ; i just stole his icon violently, and his program no longer works so i made mine (thanks to him all seriousness)

![image](https://github.com/user-attachments/assets/8b6f93ca-aa7e-455c-a30c-c716b6a4703f)

supposed to pair vga groups and audio groups from lspci and show an output of them

supposed to also work closed source nvidia drivers and open source nvidia drivers

no idea if it works with other distros, i have no idea at all for most of it.

only tested on cachyos / arch. 

dracut = untested |
initramfs = untested |
mkinitcpio = tested |

please write if you have issues

run

`git clone https://github.com/azurkytheturkey/gpu-passthrough-gtk`

`cd gpu-passthrough-gtk`

`makepkg -si`

![image](https://github.com/user-attachments/assets/966884b9-503e-42c6-ab38-6116dfbcfadd)
