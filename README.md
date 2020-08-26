# nametweaker
Tweak the name and other user settings on Leapfrog MyOwnLeaptop devices

Usage: `python3 nametweaker <new_name> <new_name.wav>`
* `<new_name>` - New name of device, limited to 8 characters
* `<new_name.wav>` - Audio file of recorded name in [WAV](https://en.wikipedia.org/wiki/WAV) format
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
