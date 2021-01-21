# my-popOS

## Distro

[Pop!_OS 20.10](https://pop.system76.com/)

## Software

- Conky @ sudo apt install conky-all

- [Discord](https://discord.com/download)

- Htop @ sudo apt install htop

- KeePassXC @Pop!_Shop (flatpak)

- Neofetch @ sudo apt install neofetch

- [Parsec](https://parsecgaming.com/downloads/)

- PulseAudio Volume Control @ Pop!_Shop (flatpak)

- Spotify @ Pop!_Shop (flatpack)

- Tweak Tool @ Pop!_Shop (debian)

- Visual Studio Code @ Pop!_Shop (debian)

## Gnome Extensions

- [User Theme](https://extensions.gnome.org/extension/19/user-themes/)

- [Hide Top Bar](https://extensions.gnome.org/extension/545/hide-top-bar/)

- [Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock/ )

- [Rounded Corners](https://extensions.gnome.org/extension/1514/rounded-corners/)

## Appearance

- [Background (Star Citizen Aegis Nautlis Concept Art)](https://starcitizen.tools/images/6/68/Nautilus_-_In_formation_attacking_in_battle_-_Port.jpg)

- After installing [Conky](#Software)

  - Copy `conky/draw_bg.lua` to `~/scripts/draw_bg.lua`

  - Copy `conky/.conkyrc` to your home folder

  - Add conky to autostart

- [Shell Theme: mcOS11 Theme](https://www.gnome-look.org/p/1220826/)

  - Extract into ~/.themes/

  - Copy both images from `images/theme` to `~/.themes/mcOS11-Shell-Dark/gnome-shell/assets`

## Other

- [Sennheiser-gsx-1200 driver](https://github.com/evilphish/sennheiser-gsx-1000)

- Firefox add [userChrome](https://www.userchrome.org/how-create-userchrome-css.html) with:

    ```css
    #webrtcIndicator {
        display: none;
    }
    ```

- Alias sudo as please with:

    ```bash
    echo please="sudo" >> ~/.bash_aliases
    source ~/.bashrc
    ```

## Old (DO NOT INSTALL)

// Needs to work with current OS version: [Komorebi](https://github.com/cheesecakeufo/komorebi/releases)

// Using Pop!_OS Dark instead of: [GTK Theme: WhiteSur GTK Theme](https://www.pling.com/p/1403328/)

// Not required after switching back to dark theme: [Spicetify-cli](https://github.com/khanhas/spicetify-cli/wiki/Installation) & [Spicetify Themes](https://github.com/morpheusthewhite/spicetify-themes)
