# Hydra Dragon Anti-virus For Linux

<p align="center">
<img src="assets/logo.png" width= 200px>
</p>

## Feautres

- Real-time protection
- Web protection
- SHA256-SHA1-MD5 calculator
- Big databases for free. Above the 65 million virus hashes here
- ClamAV on Python
- Rootkit scanner are united in one python script
## Download

Download full version [here](https://mega.nz/folder/n85EkQwa#6E6xSXO5Y2NQ4rzrg-nIzA)

### Read before using

- Don't forget give permission access.
- It really disconnect infected ip address and it deletes file so be careful!
- Don't forget to use clamonacc
- Test the suspicous file in home folder
## Contact
<a href="https://discord.gg/W2N27aF5"><img src="https://img.shields.io/discord/72895893221067986?style=flat-square&logo=appveyor"></a>
### semaemirhan555@gmail.com
## License
Public Domain License ![image](https://github.com/HydraDragonAntivirus/Hydra-Dragon-Antivirus-Linux/assets/142328963/c2679d99-7255-404b-aa5a-0e123d793645)
## How To Give Root Access To Program
sudo chown root:root Antivirus.py
sudo chmod +s Antivirus.py
## Others
virusdomainslistsuperbig is same as ultimatehostblacklist.
## Current Statics
I have **65141779+** normal virus hashes **647131+** virus or illegal websites IP address list  **2.5 million** virus or safe website. Total fuzzy hashes
**4856017**
## Detection Rate
ClamAV 60% Hydra Dragon Antivirus 65%
## Collected Datas
No data collected
## Installation On Arch Linux For Beginners
### Please Setup Your Arch Linux At Virtual Machine Antivirus Might Be Crash Your System
### Tested On Cachy OS And If You Looking For Debian Tested On Kali Linux And It Worked
sudo pacman -Sy
sudo pacman -S base-devel
sudo pacman -S python
sudo pacman -S python-tlsh
sudo pacman -S strace
sudo pacman -S python-pyinotify
sudo pacman -S rkhunter
sudo pacman -S clamav
sudo pacman -S firejail
### Download This Files
http://database.clamav.net/main.cvd
http://database.clamav.net/daily.cvd
Save at Downloads
cd
cd Downloads
git clone https://aur.archlinux.org/chkrootkit.git
cd chkrootkit/
make pkg -si
Then check installation by typing chkrootkit
cd ..
Then type sudo clamscan
Then you got this error LibClamAV Error: cli_loaddbdir: No supported database files found in /var/lib/clamav
ERROR: Can't open file or directory 
To solve this do that:
sudo cp main.cvd /var/lib/clamav/
sudo cp daily.cvd /var/lib/clamav/
If you got banned try in 24 hours
Type sudo clamscan
Installing ssdeep:
git clone https://github.com/DinoTools/python-ssdeep.git
cd ssdeep
python setup bild
sudo python setup.py install
cd ..
### Download Antivirus from mega.nz link: https://mega.nz/folder/n85EkQwa#6E6xSXO5Y2NQ4rzrg-nIzA
Save At Downloads
unzip Antivirus.zip
sudo passwd
Login your root account
Type pwd to learn your folder location
Then go Antivirus folder by Dolphin 
Open the terminal at this folder by Alt+Shift+F4
Type python Antivirus.py you are done
If you have a problem create issue topic
