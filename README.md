# Avalon Valley
![alt text](https://raw.githubusercontent.com/jnk181/avalonvalley-login/refs/heads/main/screenshot.webp)
This login theme was inspired by MondySpartan's Avalon Valley concept: https://x.com/tehmondspartan/status/1808115427425636665/photo/1
# Features and notes
* config.js - Configuration file
* Video background

# Installation
## Any
* Install `lightdm` and `web-greeter`
** Arch Linux: Official repos -> `lightdm`, AUR -> `web-greeter`
* Set `web-greeter` as the greeter in `/etc/lightdm/lightdm.conf`
* Download this repository as a .zip and extract it to a new folder named "AvalonValley"
* Copy `./AvalonValley` to `/usr/share/web-greeter/themes/` with `sudo cp -r AvalonValley /usr/share/web-greeter/themes`
* Set the `web-greeter` theme to `AvalonValley` in `/etc/lightdm/web-greeter.yml`

# To-do
* Sessions (Desktop environment) combo box picker
* The `.widget-clock` UI could be improved
* Color schemes
