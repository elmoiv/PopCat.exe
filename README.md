# PopCat.exe
Turn your Windows Recycle Bin into the famous and beloved POP CAT :)

***Turn the sound on for full experience***

https://user-images.githubusercontent.com/31712173/169914198-80495676-86e9-4fb1-a310-5a61919d3fdc.mp4


# Requirements
You need to download the following files:
- [Pop Cat Closed DLL](https://github.com/elmoiv/PopCat.exe/blob/main/requirements/popCatClosed.dll?raw=true)
- [Pop Cat Open DLL](https://github.com/elmoiv/PopCat.exe/blob/main/requirements/popCatOpen.dll?raw=true)
- [Pop Cat Sound](https://github.com/elmoiv/PopCat.exe/blob/main/requirements/popCatSound.wav?raw=true)

*Thanks to [ajenpan](https://github.com/ajenpan): Pop Cat icons extensions are renamed to .dll to enable auto refresh without editing registery*
# How to

### Replacing Recycle Bin Icons
- Open RUN **(via Windows Key + R)**
- Type: `desk.cpl ,5`
- Click on ***Recycle Bin (full)*** and change icon to ***Pop Cat Closed Icon***
- Click on ***Recycle Bin (empty)*** and change icon to ***Pop Cat Open Icon***
- Click OK

![image](https://user-images.githubusercontent.com/31712173/169913034-56a43164-a3d5-4ef3-bc4c-3d2155c1aee4.png)

<!-- ### Enable Automatic Refresh
- Open RUN **(via Windows Key + R)**
- Type: `regedit`
- Go to: `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CLSID\{645FF040-5081-101B-9F08-00AA002F954E}\DefaultIcon`
- You will see 3 keys:
  - (Default)
  - empty
  - full
- If each key value ends with `.ico`, Add `,0` at the end of each value.

![image](https://user-images.githubusercontent.com/31712173/169913157-8ec2e500-5431-40fb-9c5e-551c051f819e.png) -->

### Add Pop Sound Effect When Emptying Recycle Bin
- Open RUN **(via Windows Key + R)**
- Type: `mmsys.cpl`
- Open Sounds tab
- Scroll to `File Explorer` section then choose `Empty Recycle Bin`
- Select ***Browse*** and choose ***Pop Cat Sound***

![image](https://user-images.githubusercontent.com/31712173/169913297-b6d3b6ab-1238-4b17-9e09-de04e78b8741.png)

### P.S: Don't leave pop cat hungry.
