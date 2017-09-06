## Setps to run (from macOS)
1. Download Hypriot image (https://blog.hypriot.com/downloads/)
1. Use Etcher (https://etcher.io/) to burn image to SD card
1. Open Disk Utility and mount the SD card
1. At shell run `touch /Volumes/Hypriot/ssh`
1. In Finder, open the `device-init.yaml` file in a text editor and change the `hostname` value to the name you want the RPi to have.
1. UnMount the SD card and put it in a RPi that is connected to the network using a cable.
1. Clone this repo
1. Change to the local repo directory
1. Run `chmod +x bootstrap.sh`
1. Run `./bootstrap.sh <ipaddress-of-your-RPi>`
    1. You will be prompted for the ssh password for the RPi 2x. If you haven't changed the default password, use `hypriot` which is the default for the Hypriot image.