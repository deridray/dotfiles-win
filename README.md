## 1. install packages
```
# chocolatey
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
# fastfetch
winget install fastfetch
# yazi
winget install sxyazi.yazi
winget install Gyan.FFmpeg 7zip.7zip jqlang.jq oschwartz10612.Poppler sharkdp.fd BurntSushi.ripgrep.MSVC junegunn.fzf ajeetdsouza.zoxide ImageMagick.ImageMagick
# cava
winget install karlstav.cava
# yasb
winget install --id AmN.yasb
# komorebi
winget install LGUG2Z.komorebi
winget install LGUG2Z.whkd
# windhawk
winget install RamenSoftware.Windhawk
```
## 2. configs

### powershell
check your profile directory using ```$PROFILE``` command and then copy and paste the settings from **here**

### terminal
open **terminal** -> **settings** -> **open json file** and paste the settings from **here**

### yasb
copy files from **here** to ```C:\Users\$USERNAME\.config\yasb```

### fastfetch
copy files from **here** to ```C:\Users\$USERNAME\.config\fastfetch```

### yazi
copy files from **here** to ```C:\Users\$USERNAME\AppData\Roaming\yazi```

### cava
copy files from **here** to ```C:\Users\$USERNAME\.config\cava```