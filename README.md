# EldenRing-Save-Manager
GUI app written entirely in Python




## Usage
#### Linux / Proton / SteamDeck

Dependencies
```
python3 -m pip install Pillow requests
```
Fedora/DNF for 'ImageTk' from 'PIL'
```
sudo dnf install python3-pillow-tk.x86_64 python3-pillow.x86_64
```
Run
```
python3 SaveManager.py
```

Pyinstaller
```
pyinstaller --onefile --windowed --icon=./data/icon.ico ./SaveManager.py ./hexedit.py ./stat_progression.py ./itemdata.py ./os_layer.py ./allitems_dict.py
```


## Features:
- Edit item quantities ( Can't add items you don't have )
- Edit character stats
- Down-level characters to meet PVP meta
- Copy characters between save files
- Restore deleted characters
- Duplicate characters within the same save file
- rename characters in-game name
- Seamless co-op .co2 extension support
- automatically patch downloaded save files with your own Steam ID
- Fix corrupt save files by recalculating checksum values
- Change quantity of Runes
- God mode (sets HP, ST, FP to 60,000)
- File recovery tool that backs up your save file before every action
- Create save and load backups
- Create save slots for various builds before respec etc.
- Update to the latest release with included updater
- Force quit EldenRing when the game locks up and even task manager wont end the process

If you like the mod or want to support future updates, please [Donate](https://www.paypal.com/donate/?hosted_button_id=H2X24U55NUJJW) via PayPal

Video Tutorial: https://youtu.be/LQxmFuq3dfg?si=sKhjtqenEUBuTvBY

![save-editor](https://user-images.githubusercontent.com/68882322/163687699-334cf9d6-f956-4509-bebc-e549fe39fd3e.jpg)

![inventory editor](https://user-images.githubusercontent.com/68882322/164989037-1cc1256d-b833-478f-a7eb-84d4974d23f8.jpg)

![v1 40](https://user-images.githubusercontent.com/68882322/161843003-dfefa2fb-ca14-4401-970a-2875bb74c943.jpg)



Icon used from https://www.deviantart.com/abdelrahman18/art/Elden-Ring-Icon-877626671
You can use this icon to replace the horrible default Elden Ring game icon.




