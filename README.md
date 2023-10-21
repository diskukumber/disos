<img align="left"> <img width="400" src="./gallery/archlinux-logo-light.png">
<img align="right"> <img width="400" src="./gallery/hyprland-logo-light.svg">


<div align="center">
<img src="https://img.shields.io/github/last-commit/KhairyIbrahim/hyprland-dotfiles?style=for-the-badge&logo=github&color=a6da95&logoColor=D9E0EE&labelColor=302D41"/>
<img src="https://img.shields.io/github/repo-size/KhairyIbrahim/hyprland-dotfiles?style=for-the-badge&logo=dropbox&color=7dc4e4&logoColor=D9E0EE&labelColor=302D41"/>
<img src="https://img.shields.io/github/stars/KhairyIbrahim/hyprland-dotfiles?style=for-the-badge&logo=powerpages&color=cba6f7&logoColor=D9E0EE&labelColor=302D41"/>
</div>

# hyprland-dotfiles
Khairy Ibrahim dotfiles for Hyprland, Wayland compositor.

# still under development
This repository will be updated as development progresses.





<details>
<summary><h1>Details</h1></summary>

|  |  |
| :-- | --- |
Distribution | [Arch Linux](https://archlinux.org/)
Compositor | [Hyprland](https://hyprland.org/)
Terminal Emulator | [Kitty](https://sw.kovidgoyal.net/kitty/)
Applications launcher | [Rofi](https://github.com/lbonn/rofi)
Bar | [Waybar](https://github.com/Alexays/Waybar)
Wallpaper| [swww](https://github.com/Horus645/swww) • [Waypaper](https://github.com/anufrievroman/waypaper)
authentication agent | [xfce-polkit](https://github.com/ncopa/xfce-polkit)
Antivirus | [ClamAV](https://www.clamav.net/) • [ClamTk](https://sourceforge.net/projects/clamtk/)
Firewall | [OpenSnitch](https://github.com/evilsocket/opensnitch) • [EtherApe](https://etherape.sourceforge.io/)
Terminal text editor | [Neovim](https://neovim.io/) • [GNU nano](https://www.nano-editor.org/)
text editor | [VSCodium](https://vscodium.com/)
Terminal File Manager | [LF](https://github.com/gokcehan/lf)
File Manager | [Nemo](https://github.com/linuxmint/nemo)
File Archiver Utility | [PeaZip](https://peazip.github.io/)
Interactive Shell | [fish](https://fishshell.com/)
System Shell | [GNU Bash](https://www.gnu.org/software/bash/)
Network management | [NetworkManager](https://networkmanager.dev/) • [NM-Applet/connection-editor](https://gitlab.gnome.org/GNOME/network-manager-applet)
Modem management | [ModemManager](https://www.freedesktop.org/wiki/Software/ModemManager/) • [Modem Manager GUI](https://sourceforge.net/projects/modem-manager-gui/)
Bluetooth | [BlueZ](http://www.bluez.org/) • [Blueman](https://github.com/blueman-project/blueman)
Login Manager | [SDDM](https://github.com/sddm/sddm)
Screen Sharing | [grim](https://github.com/emersion/grim) • [slurp](https://github.com/emersion/slurp) • [swappy](https://github.com/jtheoof/swappy) • [OBS Studio](https://obsproject.com/)
Notification Daemon | [SwayNotificationCenter](https://github.com/ErikReider/SwayNotificationCenter) • [SwayOSD](https://github.com/ErikReider/SwayOSD)
Input Tools | [gestures](https://gitlab.com/cunidev/gestures)
Screen locker | [gtklock](https://github.com/jovanlanik/gtklock) • [userinfo-module](https://github.com/jovanlanik/gtklock-userinfo-module) • [Mugshot](https://github.com/bluesabre/mugshot) • [powerbar-module](https://github.com/jovanlanik/gtklock-powerbar-module) • [playerctl-module](https://github.com/jovanlanik/gtklock-playerctl-module)
Clipboard Manager | [CopyQ](https://hluk.github.io/CopyQ/)
Theme Manager | [nwg look](https://github.com/nwg-piotr/nwg-look) • [Kvantum](https://github.com/tsujan/Kvantum) • [qt5ct](https://github.com/desktop-app/qt5ct)
Theme | [Catppuccin](https://catppuccin-website.vercel.app/)
Cursor And Icon Pack | [Material Cursors](https://github.com/varlesh/material-cursors) • [Papirus Icon Pack](https://github.com/PapirusDevelopmentTeam)
Audio Control | [pavucontrol](https://github.com/pulseaudio/pavucontrol) • [pasystray](https://github.com/christophgysin/pasystray) • [QjackCtl](https://github.com/rncbc/qjackctl)
Power Management | [TLP](https://github.com/linrunner/TLP) • [TLPUI](https://github.com/d4nj1/TLPUI) • [auto cpufreq](https://github.com/AdnanHodzic/auto-cpufreq) • [Slimbook Battery](https://github.com/Slimbook-Team/slimbookbattery) • [PowerTOP](https://github.com/fenrus75/powertop) • [swayidle](https://github.com/swaywm/swayidle)

</details>


  # Features
- Hyprland gestures, - 3 Finger Swipe Switch Workspace.
- Waybar Taskbar, Mouse Right Click Minimize Application.
- Waybar Taskbar, Mouse Middle click Close Application.
- Waybar Taskbar, Mouse Left Click Maximize or Active Application.
- Hyprland Super + Mouse Scroll Switch Workspace.

## screenshots
![Screenshot](/gallery/1.png)


## Some important Key bindings
- Super + Shift + Q (Exit hyprland)
- Super + Q (kills active window)
- Super + R (Applications launcher)
- Super + Enter (Terminal Emulator)

## Work In Progress
- [x] Adding Taskbar Module to Waybar.
- [ ] Setting Taskbar to only show applications of current Active workspace.
- [ ] Adding Workspaces Module to Waybar.
- [ ] Fix Mouse Right Click Minimize Application Not Working in Waybar Taskbar.
- [x] Adding System Tray Module to Waybar.
- [x] Adding show current Active Window to Waybar.
- [x] Adding custom Application launcher Module to Waybar.
- [ ] More Customizations for Waybar - Clock, Network Monitoring, etc.

# known issues
- Flameshot and OBS, can't capture desktop.
- Some of Xorg Applications (X11), does not work with Wayland session (XWayland).
- Some of native Wayland Applications, does not work.
- wlr Modules working in config files but doesn't show up on waybar.


## INSTALLATION
<div align="left">

<details>
<summary><h3>Hyprland Stuff</h3></summary>

- Installation using yay

```sh
## Hyprland Stuff
yay -S hyprland-nvidia xdg-desktop-portal-hyprland waybar swaync swww
rofi-lbonn-wayland-git xfce-polkit swayosd-git swayidle gestures gammastep
gtklock gtklock-playerctl-module gtklock-powerbar-module gtklock-userinfo-module

```
</details>





<details>
<summary><h3>Dependencies</h3></summary>


- Installation using yay


```sh
yay -S ffmpegthumbnailer tumbler xorg-xwayland xwaylandvideobridge-cursor-mode-2-git
qt5-wayland qt6-wayland gtk4 bluez bluez-utils blueman copyq wireplumber mugshot lsb-release
pamixer brightnessctl playerctl grim slurp swappy mtpfs gvfs gvfs-mtp gvfs-gphoto2
```
</details>




<details>
<summary><h3>Bluetooth And Network</h3></summary>


- Installation using yay


```sh
yay -S bluez bluez-utils blueman networkmanager network-manager-applet
```
</details>





<details>
<summary><h3>themes</h3></summary>

- Installation using yay

```sh
## Dependencies
yay -S nwg-look kvantum qt5ct kvantum-theme-catppuccin-git papirus-icon-theme papirus-folders-catppuccin-git
catppuccin-gtk-theme-latte catppuccin-gtk-theme-frappe catppuccin-gtk-theme-macchiato catppuccin-gtk-theme-mocha
```
</details>





<details>
<summary><h3>Fonts</h3></summary>

- Installation using yay

```sh
## Dependencies
yay -S noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra ttf-noto-nerd
```
</details>




<details>
<summary><h3>NVIDIA drivers</h3></summary>

- Installation using yay

```sh
## Dependencies
yay -S nvidia-dkms nvidia-utils nvidia-settings libva libva-nvidia-driver 
```
</details>
