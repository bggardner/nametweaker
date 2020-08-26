# nametweaker
Tweak the name and other user settings on Leapfrog MyOwnLeaptop devices

Usage: `python3 nametweaker.py <new_name> <new_recording>`
* `<new_name>` - New name of device, limited to 8 characters
* `<new_recording>` - Audio file (path) of recorded name in [WAV](https://en.wikipedia.org/wiki/WAV) or [MP3](https://en.wikipedia.org/wiki/MP3) format

Example: `python3 nametweaker.py mychild mychild.mp3`

MP3s of the stock Leapfrog name recordings can be retrieved via `http://lfccontent.leapfrog.com/myname/audio/en_us/preview/NOM_xxxx.mp3`, where `xxxx` is a number from `0001` (Aaron) to `0984` (Zion).
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
