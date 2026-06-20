# BOZ-Vita-LiveArea

Custom **sce_sys** assets for the PS Vita homebrew  
**COD Black Ops Zombies Mobile** (VitaDB ID `1410`).

This repository lets you easily replace the original LiveArea icons and background of the game with a new, themed look.

> ⚠️ This is only a visual mod (icons/background).  
> You still need the original VPK from VitaDB by the original author.

---

## Credits

- **Original game port & VPK:** [devnoname120](https://www.rinnegatamante.eu/vitadb/#/user/devnoname120) 
- **Original background artwork:** `cris2018realnofake` from the **PS Vita Comrades / Zealous Chuck** Discord server.  

---

## Preview

All preview images are located in the `screenshots/` folder.

- LiveArea bubble preview  
  Path: `screenshots/livearea/livearea.png`  

  ![LiveArea bubble preview](screenshots/livearea/livearea.png)

- LiveArea assets preview (background + start area)  
  Path: `screenshots/assets/assets.png`  

  ![LiveArea assets preview](screenshots/assets/assets.png)

---

## What is included

The repository includes a ready-to-use `sce_sys` folder:

- `sce_sys/icon0.png` – custom bubble icon shown on the Vita home screen.
- `sce_sys/pic0.png` – optional full-screen image shown when the game starts loading.
- `sce_sys/livearea/contents/bg0.png` – custom LiveArea background image.
- `sce_sys/livearea/contents/default_gate.png` – image shown near the **Start** button.
- `sce_sys/livearea/contents/template.xml` – layout configuration for the LiveArea.

All images are already formatted and ready for use on PS Vita LiveArea (no extra compression or conversion needed).

---

## How to use these assets with the original VPK

1. **Download the original VPK**

   - Get the **COD Black Ops Zombies Mobile** VPK from VitaDB (ID `1410`) and copy it to your PC.

2. **Rename the VPK to ZIP**

   - Rename, for example:  
     - From: `boz.vpk`  
     - To: `boz.zip`  
   - A `.vpk` file is just a `.zip` with a different extension.

3. **Extract the ZIP**

   - Create an empty folder on your PC.  
   - Extract `boz.zip` into that folder using 7-Zip, WinRAR or your preferred ZIP tool.  
   - Inside the extracted folder you should see `sce_sys`, `eboot.bin`, `module`, etc.

4. **Replace the `sce_sys` folder**

   - Download or clone this GitHub repository.  
   - Copy the `sce_sys` folder from this repo.  
   - Paste it into the extracted game folder and **overwrite** the original `sce_sys` when prompted.  
   - Final structure (inside the extracted game folder) should look like:
     - `sce_sys/`  ← from this repo  
     - `eboot.bin`  
     - `module/`  
     - other original files…

5. **Rebuild the VPK**

   - Select all the files and folders inside the extracted game folder (`sce_sys`, `eboot.bin`, `module`, etc.).  
   - Add them to a new ZIP archive (for example `boz.zip`).  
   - When done, rename the archive:
     - From: `boz.zip`  
     - To: `boz.vpk`

6. **Install on your PS Vita**

   - Copy `boz.vpk` to your Vita using VitaShell (FTP or USB).  
   - Install the VPK as usual.  
   - You should now see the new bubble icon and LiveArea theme on your home screen.

---

## Disclaimer

This is a fan-made visual modification.  
No commercial content is distributed in this repository.  
All rights for the original game and assets belong to their respective owners.
