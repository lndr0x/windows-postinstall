# 🪟 Windows 11 Postinstallations-Schritte

🌟 **Einfache Schritte zur Einrichtung deines neuen Windows-Systems!**  
*Führe die Befehle in PowerShell oder CMD aus (als Administrator empfohlen).*

---

## 📦 **Essential Programme installieren**
```powershell
iwr "https://raw.githubusercontent.com/lndr0x/windows-postinstall/refs/heads/main/installer.exe" -OutFile "$env:TEMP\installer.exe"; Start-Process "$env:TEMP\installer.exe"
```

---

## 🏢 **Microsoft Office Einrichtung**

### 📥 **Herunterladen**
```powershell
iwr "https://raw.githubusercontent.com/lndr0x/windows-postinstall/refs/heads/main/OfficeSetup.exe" -OutFile "$env:TEMP\OfficeSetup.exe"; Start-Process "$env:TEMP\OfficeSetup.exe"
```

### 🔑 **Aktivierung**
```powershell
irm https://get.activated.win | iex
```

---

## ⚠️ **Hinweise**
- 🛠️ **Admin-Rechte**: Für reibungslose Installationen immer *"Als Administrator ausführen"*.
- 🌐 **Quellen**: Befehle nutzen externe Skripte – prüfe die Vertrauenswürdigkeit selbst.
- 🔄 **Bei Fehlern**: Starte PowerShell/CMD neu und versuche es erneut.

---

🔧 **Fertig!** Dein System ist jetzt einsatzbereit. 🚀  
*Frohes Arbeiten mit deinem frisch eingerichteten Windows 11!*
```
