
# Status

# Gallery

## System

<details><summary>💤 Zsh</summary></details>

<details><summary>🦊 Chromium</summary></details>

<details><summary>🔔 Dunst</summary></details>

<details><summary>🚀 Rofi</summary></details>

<details><summary>🔮 Polybar</summary></details>

## Communication

<details><summary>📧 Neomutt</summary></details>

<details><summary>🌀 Discord</summary></details>

## Development

<details><summary>🔥 NeoVim</summary></details>

<details><summary>💹 GnuPlot</summary></details>

<details><summary>📈 MatPlotLib</summary></details>

<details><summary>📜 LaTeX</summary></details>

<details><summary>📔 Markdown</summary></details>

## Utility

<details><summary>💻 Monitors</summary></details>

<details><summary>📰 PDF's</summary></details>

<details><summary>🗃️ Files</summary></details>

<details><summary>🗓️ Calendar</summary></details>

<details><summary>📅 Habits</summary></details>

<details><summary>📑 Scratchpad</summary></details>

## Entertainment

<details><summary>🔊 Audio</summary></details>

<details><summary>📰 News</summary></details>

<details><summary>🎁 Misc</summary></details>

<details><summary>📁 Images</summary></details>

# Table of Content

<!-- vim-markdown-toc Marked -->

* [Overview](#overview)
* [Applications](#applications)
  * [System](#system)
  * [Tools](#tools)
    * [Communication](#communication)
    * [Development](#development)
    * [Science](#science)
    * [Organisation](#organisation)
    * [Entertainment](#entertainment)
      * [Media](#media)
      * [Games](#games)
      * [Misc](#misc)
    * [Utility](#utility)
      * [System](#system)
      * [Monitors](#monitors)
        * [System](#system)
        * [Network](#network)
      * [Misc](#misc)
    * [Security](#security)
    * [Theming](#theming)
* [File Structure](#file-structure)
* [Aspects](#aspects)
* [Dependencies](#dependencies)
  * [Installation](#installation)
* [License](#license)
* [Credit](#credit)

<!-- vim-markdown-toc -->

# Overview

This repo contains all my system-wide configuration. Let me clear something up.
**This ISN'T my dotfiles**. My [dotfiles](aspects/dotfiles) are a subset of
this repo. I have other things like my [neovim](aspects/nvim) config,
[systemd](aspects/systemd), [email](aspects/email), etc. I have more
information on each aspect in the root folder of each of the aspects. 

# Applications

## System [konfigurieren]
- 💤 [Zsh](): My main shell [x]
- 💠picom-tryone-git(https://github.com/yshui/picom): A lightweight compositor for X11[x]

### Login?
- lightdm-slick-greeter	display manager config
- lightdm	display manager

### Gnome
- gnome-disk-utility	partition manager
- gnome-recipes	recipe manager

### Keyring  [Fertig]
- gnome-keyring	serves as the system keyring.[x]
### Windowmanager [Fertig]
-  [i3](https://github.com/Airblader/i3): Tiling window manager [x]

### Xserver
- xorg-server	is the graphical server. [x]
- xorg-xwininfo	allows querying information about windows.
- xorg-xprop	is a tool for detecting window properties.
- xorg-xrdb	is a tool for detecting window properties.
- xorg-xev	subscribe to x events.
- xorg-xkill	kill x windows.[x]
- xorg-xdpyinfo	aids with resolution determination and screen recording.
- xorg-xbacklight	enables changing screen brightness levels.
- xdg-user-dirs	allows changing default dirs [x]
- xdg-utils	XDG utils[x]

### Browser[Konfigurieren]
 - 🦊[Chromium](https://github.com/chromium/chromium):My main browser  [x]
 - w3m	web browser and pager[x]

### Taskbar [konfigurieren]
- 🔮[polybar](https://github.com/polybar/polybar): Customizable taskbar.[x]
- ✖️[xmenu](https://github.com/phillbush/xmenu): Modular start menu. [x]

### Rofi [konfigurieren]
- 🚀[rofi](https://github.com/davatorium/rofi): Application launcher.[x]
- [rofi-emoji](https://github.com/Mange/rofi-emoji): An emoji selector plugin for Rofi [x]
- [rofi-power-menu](https://github.com/jluttine/rofi-power-menu/blob/master/rofi-power-menu): Power menu for `rofi` [x]
- rofi-greenclip	access clipboard thru rofi. [x]
- [dmenu-hotkeys](https://github.com/maledorak/dmenu-hotkeys): Searchable i3 keybinds for `rofi` or `dmenu` [x]

- [kdeconnect](https://community.kde.org/KDEConnect): Control system from phone.[x]
- [flameshot](https://github.com/lupoDharkael/flameshot): Robust screenshotting tool[x].
- [slop](https://github.com/naelstrof/slop): Screen region selector. [x]
- [xclip](https://github.com/astrand/xclip): Scriptable clipboard utility. [x]

### Terminal [Konfigurieren]
- [rxvt-unicode](https://sw.kovidgoyal.net/kitty/): My main terminal.[x]
- tmux	terminal multiplexer(copycat,yank,open,prefixhighlight,sessionist,fpp,urlview,mapping)[x]
- neofetch	system info in console [x]
- openssh	SSH server [x]

## Tools

### Communication [konfigurieren]
- ✉️[neomutt](https://github.com/neomutt/neomutt): TUI email client.
- ✉️[outlook](): implementation of outlook for linux [x]
- 🌀[discord](https://discord.com/): GUI Discord client. [x]
- [teams]():implementation of microsoft teams for arch linux [x]
- 💬[weechat](https://github.com/weechat/weechat): Terminal IRC client. [x]
- [tuir](https://gitlab.com/ajak/tuir): TUI Reddit client.[x]
- [kdeconnect-sms](https://community.kde.org/KDEConnect): Send SMS from your system.[x]
- zoom [x]
- [slack-desktop](): implementation of Slack desktop [x]
- webex-bin [x]
  
### School and Writing[Nahezu vollständig]
- ocrfeeder	Optical Character Recognition[x]
- texlive-bibtexextra	Latex shit [x]
- texlive-most		Latex shit [x]
- texlive-fontsextra	Latex shit [x]
- texlive-core		Latex shit [x]
- texlive-science	Latex shit [x]
- texlive-latexextra	Latex shit [x]
- texlive-music		Latex shit [x]
- texlive-humanities	Latex shit [x]
- texlive-formatsextra	Latex shit [x]
- xournalpp	notetaking app with pen/touch support [x]
- [glow](https://github.com/charmbracelet/glow): CLI/TUI markdown reader/previewer[richte vscode ein][x]
- marksman-bin	Markdown LSP.[x]
- 📜[zathura](https://wiki.archlinux.org/index.php/Zathura): Lightweight PDF reader. [x]
- zathura-pdf-mupdf	allows mupdf pdf compatibility in zathura.[x]
- okular	GUI PDF viewer[x]
- zotero	research assistant. [x]
- minder	mind mapping application
- sc-im	is an Excel-like terminal spreadsheet manager.
- Office suit

### Development
#### IDEs [Konfigurieren]
- 🔥[NeoVim](https://github.com/neovim/neovim): Amazing text editor.(ultisnips,autoload,ftplugin, lanservers,lua,misc,pythonx,spell) Supportet in (python,cpp,cmake,c#,c,SQL,Maria/MongoDB,HTML,CSS,tailwindcss,Javascript,Php,Ruby,Perl,Java,Rust,Swift,Docker,Go,Dart,Kotlin,Lua,Vimscript,Bash,Solidity,Latex,yaml,json,csv [x]
- vim	vanilla vim [x]
- [codium](https://github.com/VSCodium/vscodium): [x]
#### Programming Language
##### R [config]
- r	R language [x]
##### Java[config]
- jdk-openjdk	OpenJDK [x]
- java-runtime-common	archlinux-java among other utils[x]
##### Javascript[config]
- eslint	javascript linter[x]
##### Bash[config]
- bash-language-server	LS for bash[x]
##### JSON [config]
- jq	JSON parser [x]
##### General[nahezu fertig]
- highlight	can highlight code output.
- python-gaphor	UML modeling tool.
- Draw.io [x]
- Structorizer [x]
- nvim-packer-git	a tidier vim with some useful features[x]
- pencil-bin	prototyping tool.[x]
- dotdrop	dotfile manager. [x]
- nativefier	make any webpage a native app [x]
##### HTML
- vscode-html-languageserver	html/css language server
- hugo	static site generator
##### PHP[config]
- phpactor	PHP language server [x]
##### Rust
- rustup	rust toolchain installer [x]
- rust-analyzer	rust LSP/compiler frontend [ist wahrscheinlich installiert]
##### Python
- python-configargparse	parse config args [installierenn]
- pyright	python language checker. [installieren]
- python [x]
- ipython[x]
##### Lua[vscode modules needed maybe another manager]
- luarocks	lua package manager[x]
##### Go[config]
- gopls	Golang language server[x]
##### C [Packages gefunden]
- ccls	C language server
- cmake-language-server	LSP for cmake.[x]
##### Node[config]
- npm	node package manager [x]
##### Radare2
- rizin	Newer better radare2 [x]
- rz-cutter	GUI for rizin reverse engineering tool [x]
- rz-ghidra	ghidra decompiler [x]
- [gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard): Modular visual interface for GDB in Python
- latex-mk	latex compiler.
- poppler	manipulates .pdfs and gives .pdf previews and other .pdf functions. [x]
- pandoc	document utilities [x]
- ctags	ctags [x]
#### Plotting [Konfigurieren]
- 📉 [gnuplot](http://www.gnuplot.info/): Graph and plot in the terminal[x]
- 📈 matplotlib [x]
#### Calculators [Configurieren]
- [hexyl](https://github.com/sharkdp/hexyl): Terminal hex viewer [x]
- [bitwise](https://github.com/mellowcandle/bitwise): Terminal based bit manipulator in ncurses [x]
- [Qalculate!](https://github.com/Qalculate): Intuitive and powerful calculator. [x]

#### Docker [Konfigurieren]
- docker	docker [x]
- docker-compose	docker-compose [x]
-[lazydocker](https://github.com/jesseduffield/lazydocker): TUI docker interface.[x]
#### Git [Größtenteils fertig]
- gh [x]
- git [x]
- [github-stats](https://github.com/IonicaBizau/github-stats): Visualize stats about GitHub users and projects in your terminal.
- [ghcal](https://github.com/IonicaBizau/ghcal): See the GitHub contributions calendar of a user in the command line.
#### AI Assistant [fertig]
- [chatgpt-shell-cli](https://github.com/santinic/how2) and[chatgpt-desktop](): Search stack overflow from the terminal [x]
- [perplexity-ai-app]()[x]
#### Debuging [fertig]
- [QDbusViewer](https://www.archlinux.org/packages/extra/x86_64/qt5-tools/files/) Dbus investigator GUI [x]

### Science [Konfigurieren]
- sigrok-cli	signal analysis software [x]
- pulseview	GUI for sigrok signal analyzer [x]
- [Desmos-Destkop](https://github.com/DingShizhe/Desmos-Desktop): Desktop desmos app.[x]
- [inkscape](https://github.com/inkscape/inkscape): Vector drawing program. [x]
- inkscape-figures [x]
- [geogebra](https://www.archlinux.org/packages/community/x86_64/geogebra/): Dynamic mathematics software with interactive graphics, algebra and spreadsheet [x]
- maxima	computer algebra system
- cantor	GUI interface for mathematical software [x]
- paraview	Data analysis and visualization [x]
- pandas	data library [x]
- prettypandas	pretty print pandas [x]
- step	physical simulator [x]
- lm_sensors	Sensors [x]
- labplot	interactive graphing of scientific data [x] vielleicht eine doppelung von paraview
- kicad	PCB/Circuit schematic GUI [x]
- mathmod	modeler for mathematical objects. [x]
- Logisim [x]

### Organisation [Konfigurieren]
- [dijo](https://github.com/NerdyPepper/dijo): Curses based habit tracker.[x]
- canbanboard
- zanshin	Tasks utility (should integrate with nextcloud)[x]
- calligra-plan	project management tool [x]
- skrooge	Personal finance manager [x]
- [Khal](https://github.com/pimutils/khal): Console calendar[x] 
- khard	contacts [x]
- korganizer	GUI calendar (should work with nextcloud) [x]

### Entertainment

#### Media
- playerctl	media controller [x]

##### NEWS[Konfigurieren]
- 📰[newsboat](https://www.archlinux.org/packages/community/x86_64/newsboat/): TUI RSS reader. [x]
- tuir	TUI reddit. [x]

  #### Music[Swaglyrics integrieren]
- [ncmpcpp](https://github.com/ncmpcpp/ncmpcpp): Lightweight console music player. [x]
- [mpd](https://github.com/MusicPlayerDaemon/MPD): Music player daemon.[x]
- spicetify-cli	spoticetify cli.[x]
- spotify	spotify. [x]
- spotify-tui	spotify TUI. [x]
- spotifyd	daemon for spotify [x]
- vlc	full featured media player and internet radio [x]
- [swaglyrics](https://aur.archlinux.org/packages/swaglyrics/)get lyrics from songs
- anoise	ambient noise tool [x]
- anoise-gui	GUI for ambient noise tool [x]
- anoise-media	media for ambient noise tool [x]
- anoise-community-extension1	ambient noise pack [x]
- anoise-community-extension2	ambient noise pack [x]
- anoise-community-extension3	ambient noise pack [x]
- anoise-community-extension4	ambient noise pack [x]
- anoise-community-extension5	ambient noise pack [x]
- pavucontrol	Pulseaudio controller [x]
- easytag	music file tagger [x]
- friture	GUI for real time audio analysis.[x]
- espeak-ng-espeak	Text to speech (symlinks to espeak for compatibility) [x]

##### Video [Konfigurieren]
- obs-studio	OBS [x]
- ffmpeg	can record and splice video and audio on the command line. [x]
- youtube-dl	can download any YouTube video (or playlist or channel) when given the link. [x]
- mpv	is the patrician's choice video player. [x]
- handbrake	GUI video transcoder. [x]
- kdenlive	Video editor [x]
- gifcurry	video editor and converter for gifs. [x]

##### Games [Configurieren]
- lutris	game manager and launcher [x]
- steam	Steam [x]
- antimicrox	gui to bind game controllers to actions and scripts[x]
- wine-staging	WINE [x]
- piper	Interact with mice/gaming mice [x]
- protontricks	various proton utilities. [x]

##### Pictures [Konfigurieren]
- cheese	take pictures throgh webcam [x]
- gimp	GIMP [x]
- blender	3D modeling and art software [x]
- digikam	Photo management software with editing capabilities [x]
- [giph](https://github.com/phisch/giph): Record gifs from your terminal.[x]
- freecad	3D Cad Modeler [x]
- krita	Drawing application [x]
- toilet	ACII art generator [x]

##### Misc[Konfigurieren]
- ✨ Visualizers
- [glava](https://github.com/jarcode-foss/glava):  OpenGL audio spectrum visualizer[x]

### Utility

#### Time [Konfigurieren]
- [peaclock](https://aur.archlinux.org/packages/peaclock/): Terminal timer and clock [x]
- kalarm	Desktop alarm [x]
- kronometer	stopwatch [x]
- ktimer	desktop timer [x]
- kcron	GUI for cron [x]


#### System [Konfigurieren]
- [baobab](https://aur.archlinux.org/packages/baobab-git/): GUI disk usage analyzer [x]
- [diskonaut](https://aur.archlinux.org/packages/diskonaut/): TUI disk usage analyzer. [x]
- 🔔[dunst](https://github.com/dunst-project/dunst): Lightweight and customizable notifier  daemon. [x]
- [gpick](https://www.archlinux.org/packages/community/x86_64/gpick/): Advanced color picker.[x]

#### Network[Konfigurieren]
- networkmanager	NetworkManager [x]
- network-manager-applet	Applet for NetworkManager [x]
- nm-connection-editor	Edit connections for NetworkManager [x]
- inetutils	network utilities [x]
- blueman	bluetooth [x]
- bluez	bluetooth [x]
- bluez-utils	bluetooth[x]
- kdeconnect	KDE Connect [x]
- pulseaudio-bluetooth	pulseaudio bluetooth [x]

#### 📊Monitors

##### System [Ausgewählt]
- [s-tui](https://github.com/amanusk/s-tui): Terminal-based CPU stress and monitoring utility.
- [bashtop](https://github.com/aristocratos/bashtop/): Terminal based graphical activity monitor written in bash.
- [glances](https://github.com/nicolargo/glances): Your system at a glance.
###### IO [Auswahl beendet]
- [iotop](https://www.archlinux.org/packages/community/any/iotop/): IO statistics. [x]
###### Energy [Auswah beendet]
- [powertop](https://www.archlinux.org/packages/community/x86_64/powertop/): Monitor system power.[x]
###### GPU [Auswahl beendet]
- [nvtop](https://www.archlinux.org/packages/community/x86_64/nvtop/): NVIDIAGPU TUI monitor. [x]
###### Process[Auswahl beendet]
- htop	process monitor [x]
- [atop](https://github.com/Atoptool/atop): System and process montior. [x]
###### Packages [Auswahl beendet]
- pkgtop	TUI package viewer.[x]
###### CPU[Auswahl beendet]
- [CoreFreq](https://github.com/cyring/CoreFreq): Console CPU monitor? [x]
- [kmon](https://github.com/orhun/kmon): TUI Kernel monitor. [x]
###### Logfiles [Auswahl beendet]
- ksystemlog	GUI log viewer [x]
- lnav(https://github.com/tstack/lnav): Better logfile viewer [x]
###### Network [config]
- [dnstop](https://aur.archlinux.org/packages/dnstop): Terminal DNS monitor. [x]
- [ethstatus](https://aur.archlinux.org/packages/ethstatus/): Ethernet status monitor. [x]
- [speedtest-cli](https://www.archlinux.org/packages/community/any/speedtest-cli/): CLI speedtest program [x]
- [termshark](https://github.com/gcla/termshark/): Wireshark implemented in a TUI.[x]
- [jnettop](https://github.com/jwilk-mirrors/jnettop): View hosts/ports taking up the most network traffic. [x]
- pingnoo	graphical traceroute/ping. (appimage is in /usr/local/bin/pingnoo) [x]
- [gping](https://github.com/orf/gping): TUI ping with graph [x]
- [bmon](https://github.com/tgraf/bmon): Bandwidth monitor. [x]



  
##### Misc
###### Better Commands [config]
- tldr	useful man pages [x]
- bat	better cat [x]
- exa	better ls [x]
- fd	find alternative [x]
- make	make shit [x]
- automake	make shit [x]
- zoxide	better cd [x]
- wget	wget [x]
- xdotool	provides window action utilities on the command line. [x]
- xcwd-git	x change working directory. [x]
- man-db	lets you read man pages of programs.[x]
###### Tools
- traceroute	track packet path
- [synonym](https://github.com/smallwat3r/synonym): Thesaurus in the terminal.
- [mapscii](https://github.com/rastapasta/mapscii): Map in your terminal. [x]
- [translate-shell](https://github.com/soimort/translate-shell): Google translate in the terminal. [x]
- [wtfuitil](https://github.com/wtfutil/wtf): Modular terminal dashboard.[x]
- [iponmap](https://github.com/nogizhopaboroda/iponmap): Commandline IP location finder. [x]
- moreutils	is a collection of useful unix tools.[x]
- perl-anyevent-i3	perl i3 bindings [x]
- perl-file-mimeinfo	perl filetype bindings [x]
- progress	show progress
- gkill-bin	interactive process killer. [x]
- reflector	automatically update mirrors[u
  GPS
- gpx-viewer	GUI to visualize GPX files
- marble	GUI globe
- marble-maps	maps for marble
- grass	Geospatial data management and analysis, GIS with CLI (different use case than QGIS).
- qgis	GIS software
- fzf	is a fuzzy finder tool. [x]
- offroad	offlien vector maps GUI

##### Security[Konfiguration]
- [Pass](https://www.passwordstore.org/): Light way of managing passwords.[x]
- [Rofi Pass](https://github.com/SingularisArt/Singularis/blob/master/aspects/dotfiles/files/.local/bin/rofi-pass): Quick program that allows you to select password via rofi.[x]
###### Firewall [Konfigurieren]
- ufw	uncomplicated firewall [x]
- gufw	graphical frontend for ufw [x]

##### Datamanagement [nahezu fertig]
- zip	zip [x]
- unrar	extracts rar's. [x]
- unzip	unzips zips. [x]
- 📁[ranger](https://github.com/ranger/ranger): Vim inspired console file manager[config] [x]
- 📁[thunar]():	GUI file manager [x]
- tree	file tree viewer [x]
- tree-sitter	[x]
- exfat-utils	allows management of FAT drives. [x]
- czkawka-gui-bin	GUI for finding duplicate/similar files.[x]
- ueberzug	Image viewer for terminal (used by ranger).[x]
- mediainfo	shows audio and video information. [x]
- gparted	partition manager [x]
- atool	manages and gives information about archives.[kombiniere mit thunar plugin und lösche vielleicht einzelne kommandos][x]
- ntfs-3g	allows accessing NTFS partitions.[x]
- dosfstools	allows your computer to access dos-like filesystems.[x]
- grub-customizer	customize GRUB bootloader

##### Hardware[konfigurieren]
- udiskie	automount daemon [x]
- simple-mtpfs	enables the mounting of cell phones.[x]
- ventoy-bin	multiboot USB drive creator [x]
- easystroke	Bind gestures to arbitrary actions.[x]

### Theming[configurieren]
- python-fzf-wal	fzf-wal utility.[x]
- feh	wallpaper setter [x]
- colorthief, colorz, and haishoku color generator[x]
#### Wal [Konfigurieren]
- [pywal](https://github.com/dylanaraps/pywal): Generate colorschemes from photos haishoku, colorthief, and colorz python modules for pywal backends.[x]
- [Zathura-Pywal](https://github.com/GideonWolfe/Zathura-Pywal): pywal colorscheme for zathura.[x]
- wal-steam [x]
- wal-discord
- [Gnuplot-Pywal](https://github.com/GideonWolfe/Gnuplot-Pywal): pywal colorscheme for gnuplot [x]
- ChromiumPywall(https://github.com/metafates/ChromiumPywal):theming chromium whit pywal [x]
- [Chameleon](https://github.com/SingularisArt/Chameleon): Automatically apply the schemes below.[x]
#### GTK[Konfigurieren]
- [oomox](https://github.com/themix-project/oomox): Generate icon themes, spotify themes, and GTK themes from pywal.[x]
- [lxappearance](https://www.archlinux.org/packages/community/x86_64/lxappearance/): GUI for selecting/viewing GTK themes. [x]
- gtk[x]
- wpgtk	theming engine.[x]
- [yad](https://github.com/v1cont/yad): Create GTK interfaces from the command line [x]
#### QT[Konfigurieren]
- [qt5ct](https://www.archlinux.org/packages/community/x86_64/qt5ct/): Qt5 configuration tool.[x]
- [qtcurve-qt5](https://www.archlinux.org/packages/community/x86_64/qtcurve-qt5/): Qt5/Qt4 config tool.[x]
- [qt5-styleplugins](https://www.archlinux.org/packages/community/x86_64/qt5-styleplugins/):Enable Qt features such as GTK theme.[x]
- qt5-tools	tools for Qt/KDE [x]
#### Plymouth [Konfigurieren]
- [Plymouth](https://wiki.archlinux.org/index.php/plymouth): Boot splash animation [x]
- [plymouth-themes](https://github.com/adi1090x/plymouth-themes): Collection of themes [x]
#### Fontviewer [Konfigurieren]
- lolcat	text color changer [x]
- [gucharmap](https://www.archlinux.org/packages/extra/x86_64/gucharmap/): GNOME interface for system fonts and font viewer[x]

#### Fonts and Icons[Fertig]
- ttf-font-awesome	Font awesome 5 [x]
- ttf-font-awesome-4	font awesome 4.[x]
- otf-font-awesome	font-awesome [x]
- nerd-fonts-complete	nerd fonts.
- ttf-symbola	symbols. [x]
- toilet	Figlet with more features[x]
- microsoft-core-fonts[x]
- [ArchdroidIcons](https://aur.archlinux.org/packages/archdroid-icon-theme-git/): For custom GTK themes.[x]
- aseprite-git	icons for theme.[x]

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

# Aspects
* **AUR**     : More info [here](./aspects/aur#readme).
* **Dotfiles**: More info [here](./aspects/dotfiles#readme).
* **Email**   : More info [here](./aspects/email#readme).
* **Homebrew**: More info [here](./aspects/homebrew#readme)
* **Node**    : More info [here](./aspects/node#readme)
* **NeoVim**  : More info [here](./aspects/nvim#readme)
* **Pacman**  : More info [here](./aspects/pacman#readme)
* **Python**  : More info [here](./aspects/python#readme)
* **Systemd** : More info [here](./aspects/systemd#readme)
* **Yum**     : More info [here](./aspects/yum#readme)

# Dependencies
- `git`: Required to clone the repo.
- `python >= 3.10`: Required to run the installation script.


### Install
Here's how I install my dotfiles

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

## License
Unless otherwise noted, the contents of this repo are in the public domain. See
the [LICENSE](LICENSE.md) for details
