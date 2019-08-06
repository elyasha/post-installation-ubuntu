# post-installation-ubuntu
This project has a really good checklist for things to do after installing Ubuntu

1. Update the system
  ```console
sudo apt update && sudo apt upgrade
```
1.2 Change the settings with the GUI of GNOME
2. (Optional) Enable additional repositories for more software
3. Customize the GNOME desktop
4. Install media codecs
  ```console
sudo apt install ubuntu-restricted-extras
```
5. Install software from the Software Center
6. Install software from the Web
7. (Optional) Use Flatpak in Ubuntu to get access to more applications
  ```console
sudo apt install flatpak
sudo apt install gnome-software-plugin-flatpak
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
8. (Optional) Opt out of data collection in Ubuntu
9. Change the look of my desktop with new themes and icons
  ```console
sudo apt install gnome-tweak-tool
```
10. Extend the usability of GNOME desktop with GNOME extensions
11. Prolong my battery and prevent overheating
  ```console
  sudo apt install tlp tlp-rdw
  sudo tlp start
  ```
12. Save your eyes with Nightlight
13. Disable automatic suspend for laptops
14. System cleaning
  ```console
  sudo apt autoremove
```
15. Going back to Unity or Vanilla GNOME (not recommended)
16. Can’t log in to Ubuntu 18.04 after incorrect password? Here’s a workaround
17. Experience the Community theme (optional)
18. Get Windows 10 in Virtual Box (if you need it)
19. Fixing minor annoyances in Ubuntu 18.04
20. What do you do after installing Ubuntu?
21. Install Synaptic
14. System cleaning
  ```console
  sudo apt install synaptic
```
22. Browse Extensions
23. (Optional) Remove Apport
  ```console
  sudo apt remove apport apport-gtk
```
24. Enable Proprietary and Canonical Partners Repositories
25. Install needed drivers
26. Get Important Firefox Addons or try other browser
27. (Optional) Check other interfaces
28. Create a Backup Plan

**Programs**
battery charge graph
caffeine extension
clion
gconf
fast
geogebra
gimp
tweaks
gnu octave
logisim
matlab
mathematica
virtualbox
dropbox
Dconf editor
chrome
notion
plank
git
plank preferences
pycharm pro
qtiplot
grace
spotify
telegram
texstudio
tilda
to do
tor browser
visual studio code
vlc
wireshark
atom
vim
asdf (ruby, erlang, golang, python, nodejs, elixir, kotlin, rust, crystal)
tmux
ssh
gitkraken
zsh
yadr
calibre

sudo apt install build-essential default-jdk libssl-dev exuberant-ctags ncurses-term ack-grep silversearcher-ag fontconfig imagemagick libmagickwand-dev software-properties-common git vim-gtk3 curl

sudo apt install postgresql-10 postgresql-contrib postgresql-server-dev-10 redis-server libhiredis-dev memcached libmemcached-dev

docker
nerdtree





**extensions**
activities configurator
applications menu
auto move windows
blyr
caffeine
clipboard indicator
coverflow alt-tab
cpu power manager
dash to dock
disconnect wifi
do not disturb
easyscreencast
expressvpn manager
log out button
media player indicator
native window placement
openweather
place status indicator
refresh wifi connections
removable drive menu
show desktop menu
show desktop button
suspend button
todo.txt
user themes
vitals
weather in the clock
workspace indicator
workspaces to dock
