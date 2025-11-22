# NepKey – Safari Web Extension  
## Installation Guide  
### Quick Links
- [English Version](#english-version)
- [Magyar Verzió](#magyar-verzió)

---

# English Version

## NepKey – Safari Web Extension  
Install Guide (No Paid Developer Account Needed)

This project contains the full Xcode source for the NepKey Safari Web Extension.  
Anyone can install it for free using Xcode and a normal Apple ID.

---

## Requirements
- macOS  
- Xcode (latest version)  
- Any Apple ID (free; NOT a paid developer account)

---

## 1. Clone the project
```
git clone https://github.com/yourusername/NepKey.git
cd NepKey
```

Or download the ZIP and unzip it.

---

## 2. Open the project in Xcode
Double-click:

```
NepKey.xcodeproj
```

---

## 3. Select the macOS App target
Top-left scheme selector → choose:

**NepKey (macOS App)**

---

## 4. Fix signing (one-time)
1. Click project in sidebar  
2. Select **NepKey** app target  
3. Open **Signing & Capabilities**  
4. Under **Team**, choose your Apple ID (Personal Team)

---

## 5. Press Run
Click **▶ Run** in Xcode.  
Safari will detect the extension.

---

## 6. Enable in Safari
Safari popup → **Allow** → **Turn On**

The extension stays installed.

---

## Updating
To update:

1. Pull latest code  
2. Open in Xcode  
3. Press Run again

---

## Troubleshooting
### “Signing required”
Select your Apple ID in **Signing & Capabilities → Team**.

### Extension not showing
Quit Safari fully → reopen.

### Icon missing
Safari → Settings → Extensions → enable NepKey.

---

# Magyar Verzió

## NepKey – Safari Web Extension  
Telepítési Útmutató

Ez a projekt tartalmazza a NepKey Safari Web Extension teljes Xcode forrását.  
Bárki telepítheti ingyen, csak Xcode és egy Apple ID kell.

---

## Követelmények
- macOS  
- Xcode  
- Bármilyen Apple ID (ingyenes)

---

## 1. Projekt letöltése
```
git clone https://github.com/yourusername/NepKey.git
cd NepKey
```

---

## 2. Xcode megnyitása
Dupla katt:

```
NepKey.xcodeproj
```

---

## 3. macOS App target kiválasztása
Bal felső sarok:

**NepKey (macOS App)**

---

## 4. Aláírás beállítása
1. Projekt → **NepKey** target  
2. **Signing & Capabilities**  
3. **Team** → saját Apple ID

---

## 5. Futtatás
Nyomj **▶ Run**-t.  
Safari érzékeli az extensiont.

---

## 6. Engedélyezés Safariban
Popup → **Allow** → **Turn On**

---

## Frissítés
Pull → Xcode → Run

---

## Hibakeresés
### “Signing required”
Team mező → Apple ID.

### Safari nem látja
Safari teljes bezárása → újraindítás.

### Nincs ikon
Safari → Settings → Extensions → NepKey bekapcsolása.
