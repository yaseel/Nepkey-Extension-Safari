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
git clone https://github.com/yaseel/NepKey-Extension-Safari.git
```

Or download the ZIP and unzip it.

---

## 2. Open the project in Xcode
Double-click:

```
Nepkey-Extension-Safari.xcodeproj
```

---

## 3. Fix signing (one-time)
1. Click Nepkey-Extension-Safari in sidebar  
2. Select **Nepkey-Extension-Safari Extension** app target  
3. Open **Signing & Capabilities**  
4. Under **Team**, choose your Apple ID (Personal Team)

---

## 4. Press Run
Click **▶ Run** in Xcode.  
Safari will detect the extension.

---

## 5. Enable in Safari
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
git clone https://github.com/yaseel/NepKey-Extension-Safari.git
```

---

## 2. Xcode megnyitása
Dupla katt:

```
Nepkey-Extension-Safari.xcodeproj
```

---

## 3. Aláírás beállítása
1. Kattints Nepkey-Extension-Safari -ra a bal oldalon  
1. Kattints a **Nepkey-Extension-Safari Extension** targetre
2. **Signing & Capabilities**  
3. **Team** → saját Apple ID

---

## 4. Futtatás
Nyomj **▶ Run**-t.  
Safari érzékeli az extensiont.

---

## 5. Engedélyezés Safariban
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
