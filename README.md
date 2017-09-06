## Setps to run
1. Download Hypriot image
1. Use Etcher to burn image to SD Card
1. At shell run `touch /Volumes/Hypriot/ssh`
1. Clone this repo
1. Change to the local repo directory
1. run `chmod +x bootstrap.sh`
1. run `./bootstrap.sh <ipaddress-of-your-RPi>`
    1. You will be prompted for the ssh password for the RPi 2x. If you haven't changed the default password, use `hypriot` which is the default for the Hypriot image.