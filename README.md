This is a fork of the original [ulauncher-system](https://github.com/iboyperson/ulauncher-system) repo. This is done in order to include my personal preference on how hibernate is treated on my system. I don't want it to use `systemctl hibernat -i`
 but the executable `hibernate` installed manually.
# Ulauncher-System

This is a extension for [Ulauncher](https://ulauncher.io/) that allows you to:

* Lock
* Log Off
* Suspend
* Hibernate
* Reboot
* Shutdown

## What sets it appart?

* It will attempt to work nicely with the Desktop Environment of you choice. Below are the currently supported DEs.
  If one of these is not detected default commands will be used if possible.
  * GNOME Based (Unity, Gnome, Etc.)
  * KDE
  * Cinnamon
  * Mate
  * XFCE
* It uses the system icon theme for all but its required icon.
* More in the future!

### Credits to [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) for the current Icon of the extension
