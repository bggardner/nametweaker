# nametweaker
Tweak the name and other user settings on Leapfrog MyOwnLeaptop devices
## Debian-based Linux Distros
```
sudo apt update
sudo apt upgrade
sudo apt install git python3-pydub sg3utils wine winetricks
winetricks -q mfc42
git clone https://github.com/mac2612/nametweaker.git
cd nametweaker
python3 nametweaker.py <new_name> <new_name.wav>
```
