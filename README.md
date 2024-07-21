# SD-MangoHud-Presets
Personal config for [MangoHud](https://github.com/flightlessmango/MangoHud), that I'm using with my Steam Deck. 

Font colors have been altered and there are some slight layout changes compared to the default look.

Preset 2 & 3 now show SlowPPT + FastPPT in real-time. This is mainly useful to make sure that the configured TDP is actually being applied when setting it with PowerTools for example. Should work on SteamOS and Bazzite.

Can be used as a template to set your own colors and layout.

## Installation
To install, just copy `presets.conf` to `/home/deck/.config/MangoHud`. You might need to enable the option to "show hidden files and folders" in your file browser, in order to see the `.config` folder. If the `MangoHud` folder does not exist, you have to create it yourself. 

Afterwards just change the "Performance Overlay Level" in the Steam Deck's UI and the changes should automatically be applied.

## Screenshots
Preset 2

![2](/screenshots/preset2.jpg?raw=true "Preset2")

Preset 3

![3](/screenshots/preset3.jpg?raw=true "Preset3")

Preset 4

![4](/screenshots/preset4.jpg?raw=true "Preset4")

## Uninstall
Simply delete `/home/deck/.config/MangoHud/presets.conf`.
