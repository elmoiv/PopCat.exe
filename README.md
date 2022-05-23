# PopCat.exe
Turn your Windows Recycle Bin into the famous and beloved POP CAT :)

# Requirements
You need to download the following files:
- [Pop Cat Closed Icon](https://github.com/elmoiv/PopCat.exe/blob/main/requirements/popCatClosed.ico?raw=true)
- [Pop Cat Open Icon](https://github.com/elmoiv/PopCat.exe/blob/main/requirements/popCatOpen.ico?raw=true)
- [Pop Cat Sound](https://github.com/elmoiv/PopCat.exe/blob/main/requirements/popCatSound.wav?raw=true)

# How to

### Replacing Recycle Bin Icons
- Open RUN **(via Windows Key + R)**
- Type: `desk.cpl ,5`
- Click on ***Recycle Bin (full)*** and change icon to ***Pop Cat Closed Icon***
- Click on ***Recycle Bin (empty)*** and change icon to ***Pop Cat Open Icon***
- Click OK

### Enable Automatic Refresh
- Open RUN **(via Windows Key + R)**
- Type: `regedit`
- Go to: `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CLSID\{645FF040-5081-101B-9F08-00AA002F954E}\DefaultIcon`
- You will see 3 keys:
  - (Default)
  - empty
  - full
- If each key value ends with `.ico`, Add `,0` at the end of each value.

### Add pop sound effect when emptying Recycle Bin
- Open RUN **(via Windows Key + R)**
- Type: `mmsys,cpl`
- Open Sounds tab
- Scroll to `File Explorer` section then choose `Empty Recycle Bin`
- Select ***Browse*** and choose ***Pop Cat Sound***

### P.S: Don't leave pop cat hungry.
