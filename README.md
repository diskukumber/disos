

# hyprland-dotfiles
Khairy Ibrahim dotfiles for Hyprland, Wayland compositor.

# still under development
This repository will be updated as development progresses.

## Details
- distribution : openSUSE Tumbleweed
- Terminal Emulator : kitty
- Applications launcher : Rofi Wayland
- Bar : Waybar
- Wallpaper : (mpvpaper) for live wallpaper / (swaybg) for static wallpaper
- Polkit : KDE Polkit

# Features
- Hyprland gestures, - 3 Finger Swipe Switch Workspace.
- Waybar Taskbar, Mouse Right Click Minimize Application.
- Waybar Taskbar, Mouse Middle click Close Application.
- Waybar Taskbar, Mouse Left Click Maximize or Active Application.
- Hyprland Super + Mouse Scroll Switch Workspace.

## screenshots
![Screenshot](/screenshots/2.png)
![Screenshot](/screenshots/1.png)
![Screenshot](/screenshots/3.png)
![Screenshot](/screenshots/4.png)

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
