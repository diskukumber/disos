<div align="center">
<img src="https://img.shields.io/github/last-commit/KhairyIbrahim/hyprland-dotfiles?style=for-the-badge&logo=github&color=a6da95&logoColor=D9E0EE&labelColor=302D41"/>
<img src="https://img.shields.io/github/repo-size/KhairyIbrahim/hyprland-dotfiles?style=for-the-badge&logo=dropbox&color=7dc4e4&logoColor=D9E0EE&labelColor=302D41"/>
<img src="https://img.shields.io/github/stars/KhairyIbrahim/hyprland-dotfiles?style=for-the-badge&logo=powerpages&color=cba6f7&logoColor=D9E0EE&labelColor=302D41"/>
</div>



# hyprland-dotfiles
Khairy Ibrahim dotfiles for Hyprland, Wayland compositor.

# still under development
This repository will be updated as development progresses.

## Details
<summary><b>LONG READ</b></summary>

* **Distribution** •  [Arch Linux](https://github.com/archlinux)
* **Window Manager** •  [Hyprland](https://github.com/hyprwm/Hyprland)
* **Terminal Emulator** •  [Kitty](https://github.com/kovidgoyal/kitty)
* **Applications launcher** •  [Rofi Wayland](https://github.com/lbonn/rofi)
* **Bar** •  [Waybar](https://github.com/Alexays/Waybar)
* **Live Wallpapers** •  [mpvpaper](https://github.com/GhostNaN/mpvpaper)
* **Static Wallpapers** •  [swaybg](https://github.com/swaywm/swaybg)
* **Polkit authentication** •  [polkit-kde-agent-1](https://github.com/KDE/polkit-kde-agent-1)
* **Antivirus** •  [ClamAV](https://github.com/Cisco-Talos/clamav) • [ClamTk](https://github.com/dave-theunsub/clamtk)
* **Firewall** •  [UFW](https://archlinux.org/packages/community/any/ufw/) • [Gufw](https://github.com/costales/gufw)
* **Terminal text editor** •  [Neovim](https://github.com/neovim/neovim)
* **text editor** •  [Visual Studio Code](https://github.com/microsoft/vscode)
* **Terminal File Manager** •  [LF](https://github.com/gokcehan/lf)
* **File Manager** •  [Nemo](https://github.com/linuxmint/nemo)
* **Interactive Shell** •  [fish](https://github.com/fish-shell/fish-shell)
* **System Shell** •  [Bash](https://archlinux.org/packages/core/x86_64/bash/)

* **Logout Menu** •  [wlogout](https://github.com/ArtsyMacaw/wlogout)
* **Screen locker** •  [swaylock effects](https://github.com/mortie/swaylock-effects)
* **Laptops**

* **Screen Brightness** •  [backlight control](https://github.com/Hendrikto/backlight_control)
* **GPU switching** •  [Optimus Manager](https://github.com/Askannz/optimus-manager) • [Optimus Manager Qt](https://github.com/Shatur/optimus-manager-qt)
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
