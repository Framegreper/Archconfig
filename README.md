# Arch Linux Configuration
My System Configuration for my Archlinux I use in my workflow
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Used Packages](#used-packages)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

To utilize these configuration files on your Arch Linux system, please follow the steps below:

1. Clone this repository to your local machine:
   ```shell
   git clone https://github.com/your-username/arch-linux-configuration.git
   ```
2. Copy the desired configuration files to their respective locations on your Arch Linux system. Be cautious while overriding any existing system files and make sure to create backups if necessary.
3. Update the configuration files according to your preferences and requirements. Make sure to read through the respective configuration files to understand their purpose and make necessary adjustments.
## Usage

The configuration files in this repository are intended to be used in an Arch Linux environment. They vary across different areas of system customization, including:

- Shell Configuration: `.bashrc`, `.zshrc`, `.profile`, etc.
- Window Manager Configuration: `.i3config`
- Terminal Emulator Configuration: `.alacritty.yml`, `.xfce4-terminal.rc`, etc.
- Editor Configuration: `.vimrc`,`.vscode-settings.json`
- and more...

Each file has its own purpose and can be utilized to customize the respective software or component.

## Used Packages
The following packages are used in this configuration:
### System
- 💤 [Zsh](https://fishshell.com/): My main shell(Doing Configuration and porting fish config and (plugins and zshrc add config directory))
- [urxvt and urxvt-resize-font-git](https://aur.archlinux.org/packages/urxvt-resize-font-git/): My main terminal [x]
- [i3](https://github.com/Airblader/i3): Tiling window manager setup the rest of the keybinds in i3(Audio, Dunst, Britghtness, other, i3, rofi, applications, school)
- 🦊 [Chromium](https://github.com/chromium/chromium):My main browser
- 🔔 [Dunst](https://github.com/dunst-project/dunst):Lightweight and customizable notification daemon (Setup)
- 🔮[polybar](https://github.com/polybar/polybar): Customizable taskbar (debug polybar (abends videos zu den plugins anschauen))
- 💠 [picom](https://github.com/yshui/picom): A lightweight compositor for X11 [install]
- 🚀 [rofi](https://github.com/davatorium/rofi): Application launcher[add all rofi features]
- ✖️ [xmenu](https://github.com/phillbush/xmenu):[x] Modular start menu (Check if the Menu Script is complete)
- [kdeconnect](https://community.kde.org/KDEConnect): Control system from phone
- [flameshot](https://github.com/lupoDharkael/flameshot):[add scripts] Robust screenshotting tool
- [giph](https://github.com/phisch/giph): Record gifs from your terminal [x]
- [slop](https://github.com/naelstrof/slop): Screen region selector[install]
- [xclip](https://github.com/astrand/xclip): Scriptable clipboard utility [x]

### Tools
#### Communication
- 🌀 [Discord](https://discord.com/):GUI Discord client. [x]
- [slack](): implementation of Slack desktop [testen]
- [teams]():implementation of microsoft teams for arch linux [testen]
- 💬 [Weechat](https://github.com/weechat/weechat): Terminal IRC client
- ✉️ [neomutt](https://github.com/neomutt/neomutt): TUI email client [installiere via muttwizard]
- [outlook](): implementation of outlook for linux [testen]
- [tuir](https://gitlab.com/ajak/tuir): TUI Reddit client. [x]
- [kdeconnect-sms](https://community.kde.org/KDEConnect): Send SMS from your system
  
#### Development
- 🔥 [Neovim](https://github.com/neovim/neovim) and [codium](https://github.com/VSCodium/vscodium): Amazing text editor for coding, 📜 LaTeX and markdown etc. [install plugins]
- 📉 [gnuplot](http://www.gnuplot.info/): Graph and plot in the terminal [install]
- 📈 matplotlib [install]
- [lazydocker](https://github.com/jesseduffield/lazydocker): TUI docker dashboard [configurate]
- [Qalculate!](https://github.com/Qalculate): Intuitive and powerful calculator [x]
- [ghcal](https://github.com/IonicaBizau/ghcal): See the GitHub contributions calendar of a user in the command line.
- [github-stats](https://github.com/IonicaBizau/github-stats): Visualize stats about GitHub users and projects in your terminal.
- [hexyl](https://github.com/sharkdp/hexyl): Terminal hex viewer [x]
- [bitwise](https://github.com/mellowcandle/bitwise): Terminal based bit manipulator in ncurses [x]
- [gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard): Modular visual interface for GDB in Python
- [QDbusViewer](https://www.archlinux.org/packages/extra/x86_64/qt5-tools/files/) Dbus investigator GUI [x]
- [chatgpt-shell-cli](https://github.com/santinic/how2) and[chatgpt-desktop](): Search stack overflow from the terminal
- [perplexity-ai-app]()

#### Productivity
- [dijo](https://github.com/NerdyPepper/dijo): Curses based habit tracker.
- canbanboard
- [Khal](https://github.com/pimutils/khal): Console calendar 
- Alternative to Khal: [Calcurse](https://github.com/lfos/calcurse): Console calendar.
- [Nextcloud client](https://www.archlinux.org/packages/community/x86_64/nextcloud-client/): Sync files with Nextcloud server
- [vdirsyncer](https://github.com/pimutils/vdirsyncer): Synchronize calendar and contacts with NextCloud
#### Science
- [Desmos-Destkop](https://github.com/DingShizhe/Desmos-Desktop): Electron desktop desmos app. [install]
- [geogebra](https://www.archlinux.org/packages/community/x86_64/geogebra/): Dynamic mathematics software with interactive graphics, algebra and spreadsheet [x]
- [inkscape](https://github.com/inkscape/inkscape): Vector drawing program. [install]
#### Entertainment
##### Media
- 📰 [newsboat](https://www.archlinux.org/packages/community/x86_64/newsboat/): TUI RSS reader [add RSS]
- [mpd](https://github.com/MusicPlayerDaemon/MPD): Music player daemon.
- [castero](https://aur.archlinux.org/packages/castero-git/): TUI for podcasts
- 🎵 Spotify whit [swaglyrics](https://aur.archlinux.org/packages/swaglyrics/)und spicetify: Spotify whit lyrics in browser or terminal
- 🎶 [cmus](https://github.com/cmus/cmus) and [cmus-notify](https://github.com/dcx86r/cmus-notify) : Lightweight console music player plus notifier
- Alternative to cmus: [ncmpcpp](https://github.com/ncmpcpp/ncmpcpp): Lightweight console music player.
#### Games
- Lutris(Steam, Epic, GOG)[Epic fehlt]

##### Misc
- ✨ Visualizers
- [cava](https://github.com/karlstav/cava): Console music visualizer
- [glava](https://github.com/jarcode-foss/glava):  OpenGL audio spectrum visualizer
- 🎁 Misc 
#### Utility
- 🗒️ Scratchpad
- 🔊 Volume
##### System
- [baobab](https://aur.archlinux.org/packages/baobab-git/): GUI disk usage analyzer [x]
- [diskonaut](https://aur.archlinux.org/packages/diskonaut/): TUI disk usage analyzer [x]
- 📜[zathura](https://wiki.archlinux.org/index.php/Zathura): Lightweight PDF reader [x]
- 📁[ranger](https://github.com/ranger/ranger): Vim inspired console file manager
- 📁[thunar]():[x]
- [dmenu-hotkeys](https://github.com/maledorak/dmenu-hotkeys): Searchable i3 keybinds for `rofi` or `dmenu`
- [gucharmap](https://www.archlinux.org/packages/extra/x86_64/gucharmap/): GNOME interface for system fonts
- [greenclip](https://github.com/erebe/greenclip): Clipboard manager
- gnome-font-viewer
- [glow](https://github.com/charmbracelet/glow): CLI/TUI markdown reader
- [rofi-emoji](https://github.com/Mange/rofi-emoji): An emoji selector plugin for Rofi
- [rofi-power-menu](https://github.com/jluttine/rofi-power-menu/blob/master/rofi-power-menu): Power menu for `rofi`
- [gpick](https://www.archlinux.org/packages/community/x86_64/gpick/): Advanced color picker [x]
- [termdown](https://github.com/trehn/termdown): Countdown timer and stopwatch in your terminal 
- [peaclock](https://aur.archlinux.org/packages/peaclock/): Terminal timer and clock
- [yad](https://github.com/v1cont/yad): Create GTK interfaces from the command line
- [dunst](https://github.com/dunst-project/dunst): Lightweight notifier.
##### 📊Monitors
###### System
- [s-tui](https://github.com/amanusk/s-tui): Terminal-based CPU stress and monitoring utility
- [CoreFreq](https://github.com/cyring/CoreFreq): Console CPU monitor
- [gotop](https://github.com/cjbassi/gotop): Terminal based graphical activity monitor
- [bashtop](https://github.com/aristocratos/bashtop/): Terminal based graphical activity monitor written in bash
- [glances](https://github.com/nicolargo/glances): Your system at a glance
- [iotop](https://www.archlinux.org/packages/community/any/iotop/): IO statistics
- [nmon](https://www.archlinux.org/packages/community/x86_64/nmon/): Configurable ncurses system monitor
- [atop](https://github.com/Atoptool/atop): System and process montior
- [powertop](https://www.archlinux.org/packages/community/x86_64/powertop/): Monitor system power
- [kmon](https://github.com/orhun/kmon): TUI Kernel monitor
- [lnav](https://github.com/tstack/lnav): Better log viewer
###### Network
- [dnstop](https://aur.archlinux.org/packages/dnstop): Terminal DNS monitor [install]
- [ethstatus](https://aur.archlinux.org/packages/ethstatus/): Ethernet status monitor [install]
- [jnettop](https://github.com/jwilk-mirrors/jnettop): view hosts/ports taking up the most network traffic
- [nload](https://www.archlinux.org/packages/community/x86_64/nload/): Monitors network traffic and bandwidth usage
- [bmon](https://github.com/tgraf/bmon): Bandwidth monitor
- [termshark](https://github.com/gcla/termshark/): Wireshark implemented in a TUI
- [gping](https://github.com/orf/gping): TUI ping with graph
- [speedtest-cli](https://www.archlinux.org/packages/community/any/speedtest-cli/): CLI speedtest program
###### Misc
- [synonym](https://github.com/smallwat3r/synonym): Thesaurus in the terminal [install]
- [mapscii](https://github.com/rastapasta/mapscii): Map in your terminal [install]
- [translate-shell](https://github.com/soimort/translate-shell): Google translate in the terminal [install]
- [wtfuitil](https://github.com/wtfutil/wtf): Modular terminal dashboard [install]
- [iponmap](https://github.com/nogizhopaboroda/iponmap): commandline IP location finder [install]
#### Security
- [Seahorse](https://security.archlinux.org/package/seahorse): GUI to manage PGP/SSH keys
- [keepassxc](https://www.archlinux.org/packages/community/x86_64/keepassxc/): Keepass GUI
Or
- [Pass](https://www.passwordstore.org/): Light way of managing passwords.
- [Rofi Pass](https://github.com/SingularisArt/Singularis/blob/master/aspects/dotfiles/files/.local/bin/rofi-pass):  Quick program that allows you to select pass password via rofi.
### Theming
- [Chameleon](https://github.com/GideonWolfe/Chameleon): Automatically apply the schemes below [configurate]
- [pywal](https://github.com/dylanaraps/pywal): Generate colorschemes from photos haishoku, colorthief, and colorz python modules for pywal backends [x]
- [Zathura-Pywal](https://github.com/GideonWolfe/Zathura-Pywal): pywal colorscheme for zathura [install]
- [Gnuplot-Pywal](https://github.com/GideonWolfe/Gnuplot-Pywal): pywal colorscheme for gnuplot [install]
- [qutewal](https://github.com/jjzmajic/qutewal): pywal theme for qutebrowser
- [oomox](https://github.com/themix-project/oomox): Generate icon themes, spotify themes, and GTK themes from pywal[x]
- [lxappearance](https://www.archlinux.org/packages/community/x86_64/lxappearance/): GUI for selecting/viewing GTK themes [x]
- [Archdroid Icons](https://aur.archlinux.org/packages/archdroid-icon-theme-git/): For custom GTK themes
- [qt5ct](https://www.archlinux.org/packages/community/x86_64/qt5ct/): Qt5 configuration tool [install]
- [qtcurve-qt5](https://www.archlinux.org/packages/community/x86_64/qtcurve-qt5/): Qt5/Qt4 config tool [x]
- [qt5-styleplugins](https://www.archlinux.org/packages/community/x86_64/qt5-styleplugins/): Enable Qt features such as GTK theme [x]
- [Plymouth](https://wiki.archlinux.org/index.php/plymouth): Boot splash animation(install)
- [plymouth-themes](https://github.com/adi1090x/plymouth-themes): Collection of themes(install)
- theming chromium whit pywal(https://github.com/metafates/ChromiumPywal)
Please make sure to install these packages on your Arch Linux system to ensure the proper functionality of the configuration files.
## File Structure

The repository's file structure is designed to maintain organization and easy accessibility. It follows a logical division based on software or component configuration.

```plaintext
.
├── .config
│   ├── i3
│   ├── alacritty
│   ├── vim
│   ├── ...
│   └── README.md
├── .zshrc
├── .bashrc
├── .vimrc
├── .emacs
├── .xinitrc
└── README.md
```

## Contributing

Contributions tothis repository are not expected, as the provided configuration files are specific to my personal preferences. However, if you come across any issues or improvements that you believe would benefit others, feel free to open an issue or pull request.

## License

This repository is licensed under the [MIT License](https://opensource.org/licenses/MIT). Please refer to the [LICENSE](LICENSE) file for more details.
