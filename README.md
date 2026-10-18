!!!!INSTALL IT AT YOUR OWN RISK AS THE CREATOR IS NOT LAIBLE TO ANY BAD CHANGES IT MAKES TO YOUR SYSTEM IF AT ALL IT DOES!!!!


This is a hyprland shell that was built for fedora and is made fully by claude ai.
It enables copr lionheartp repo to install hyprland and quickshell.
The installer installs multiple dependencies needed for the shell to work.
To install run the .install file as an executable program or drag and drop the file into the terminal and press enter.
Please note the this shell is mostly a test of ai.


Dependencies:
  core         Hyprland (the compositor) and Quickshell (runs the shell)
               hyprland quickshell
  qt           Qt 6 parts the shell is built on
               qt6-qtdeclarative qt6-qtsvg qt6-qtwayland qt6-qtmultimedia qt6-qtimageformats
  portals      File pickers and screen sharing
               xdg-desktop-portal xdg-desktop-portal-hyprland xdg-desktop-portal-gtk hyprland-guiutils
  audio        Volume, microphone, sounds
               pipewire wireplumber pipewire-pulseaudio pipewire-utils pulseaudio-utils sound-theme-freedesktop
  network      Wi-Fi and Bluetooth
               NetworkManager
  media        Music widget and its beat, previews of video wallpapers
               playerctl cava ffmpeg-free
  display      Brightness, night light, battery
               brightnessctl upower hyprsunset
  capture      Screenshots and screen recording
               grim slurp wf-recorder ImageMagick
  clipboard    Clipboard history, on-screen keyboard typing
               wl-clipboard cliphist wtype
  theming      Making other apps follow the shell colours
               qt6ct qt5ct adw-gtk3-theme
  fonts        Interface font and emoji
               rsms-inter-fonts google-noto-color-emoji-fonts
  tools        Helper scripts (python, keyring, notifications, downloads)
               python3 python3-gobject gnome-keyring libnotify xdg-utils curl git inotify-tools
  apps         Default terminal and file manager (any others work too)
               kitty nautilus
  rgb          RGB lighting on keyboards, mice, fans (optional)
               openrgb openrgb-udev-rules
  controllers  Game controller support
               steam-devices

