# Meno POS Desktop

Windows x64 desktop shell for Meno POS. It loads the same Angular POS application and adds local Windows thermal printing without browser confirmation dialogs.

```powershell
Meno-POS-Desktop.exe
Meno-POS-Desktop.exe --start-url=http://localhost:4200
```

The default address is `https://meno.pandahouse2025.ge`. Device printer bindings are local. Each receipt kind can use a different Windows printer and a width from 40mm to 100mm.

Create a `release/x.y.z` tag from `release/x.y`. GitHub Actions builds the NSIS installer, publishes the GitHub Release, and makes it available for startup updates.
