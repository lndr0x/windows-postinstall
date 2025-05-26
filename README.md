# Postinstall Steps für Windows 11

### Programme installieren
  ```
iwr "https://raw.githubusercontent.com/lndr0x/windows-postinstall/refs/heads/main/installer.exe" -OutFile "$env:TEMP\installer.exe"; Start-Process "$env:TEMP\installer.exe"
  ```

### Office installieren & aktivieren
Office downloaden:
  ```
iwr "https://raw.githubusercontent.com/lndr0x/windows-postinstall/refs/heads/main/OfficeSetup.exe" -OutFile "$env:TEMP\installer.exe"; Start-Process "$env:TEMP\OfficeSetup.exe"
  ```


Office aktivieren:
  ```
irm https://get.activated.win | iex
  ```
