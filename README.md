# EldenRing-Save-Manager
GUI app written entirely in Python

## Usage
#### Windows
[Download Latest Release]()

#### Linux / Proton / SteamDeck

Run
```
python3 SaveManager.py
```

Pyinstaller
```
pyinstaller --onefile --windowed ./SaveManager.py ./hexedit.py ./stat_progression.py ./itemdata.py ./os_layer.py ./allitems_dict.py
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
- File recovery tool that backs up your save file before every action
- Create save and load backups
- Create save slots for various builds before respec etc.
- Update to the latest release with included updater
- Force quit EldenRing when the game locks up and even task manager wont end the process
> Tested with Elden Ring version 1.16.1

<details>
<summary><h2>Changes made to the main project</h2></summary>

- removed unnecessary dependencies
- removed update feature
- removed features that do not work anymore
- improved ui
- reworked code
</details>

Video Tutorial: https://youtu.be/LQxmFuq3dfg?si=sKhjtqenEUBuTvBY

![save-editor](https://user-images.githubusercontent.com/68882322/163687699-334cf9d6-f956-4509-bebc-e549fe39fd3e.jpg)

![inventory editor](https://user-images.githubusercontent.com/68882322/164989037-1cc1256d-b833-478f-a7eb-84d4974d23f8.jpg)

![v1 40](https://user-images.githubusercontent.com/68882322/161843003-dfefa2fb-ca14-4401-970a-2875bb74c943.jpg)
