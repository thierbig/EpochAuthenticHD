# Authentic HD – Faithful / Curated, Enhanced + DXVK

> **Works with Project Epoch Reborn.** This collection is kept up to date against the current Reborn client.

A carefully selected **Epoch Graphics Collection** with essential upscaling patches, subtle world upgrades, and Vulkan support via DXVK 2.7.1 for improved graphics performance.

Keep the authentic Classic WoW look, just a little more crisper! Also adds many uniquely voice-acted NPCs and updated player sounds. Refreshes zone music/ambience. Blends better for veteran players.

**UPDATED 11/08/2026**

> ⚠️ **Letters changed in this update.** Epoch now ships its own **PATCH-D** and **PATCH-M**, so the collection was moved up a letter to get out of the way: old **D → E**, old **E → F**, old **F → G**, old **M → N**.

Download here: [My Google Drive](https://drive.google.com/file/d/1mP0MwN_L3JG6ZsAt6NNkVMI6jCmpR87n/view?usp=sharing)

In the epoch_live (WoW folder) folder, extract the .mpq files into the `Data` folder and the `Icons` folder into the Interface folder.

**WARNING: If your PC isn't powerful or feel you want more FPS, do not extract the HD Spells/Items `Icons`!**

**If you want OLD Original Vanilla Character Models for your own character, delete PATCH-E**

## 1. Epoch / WotLK MPQ Setup (Just for reading information)

---

## Core Game Files  
⚠️ **Do not change or delete these!** These are shipped by the game and kept updated by the launcher — if you overwrite one, the launcher will either re-download it or you will break the client.

- **COMMON.MPQ**  
- **COMMON-2.MPQ**  
- **EXPANSION.MPQ**  
- **LICHKING.MPQ**  
- **PATCH.MPQ**  
- **PATCH-2.MPQ**  
- **PATCH-3.MPQ**  
- **PATCH-A.MPQ**  
- **PATCH-B.MPQ**
- **PATCH-C.MPQ**
- **PATCH-D.MPQ** — Epoch's own UI patch (custom FrameXML/GlueXML: GM tickets, raid browser, spell scaling, character select). **Not** the old HD character models — that is PATCH-E now.
- **PATCH-M.MPQ** — shipped by Epoch
- **PATCH-Y.MPQ**  
- **PATCH-Z.MPQ** *(if present)*

---

## Custom MPQs Added

- **PATCH-4.MPQ** — Vanilla NPC texture upscale 2x *(unknown modder)*  
- **PATCH-5.MPQ** — Vanilla armor items texture upscale 2x *(unknown modder)*  
- **PATCH-E.MPQ** — **HD Character Models from WotLK HD**, maintained by *Loriendal*, then updated by *Bset* for Epoch *(Bset Patch-E)*. *(was PATCH-D)*
- **PATCH-F.MPQ** — Faithful Upscaled Textures Epoch *(Vish patch-K)* *(was PATCH-E)*
- **PATCH-G.MPQ** — Better Trees *(OdysseyMods)* *(was PATCH-F)*
- **PATCH-N.MPQ** — Faithful Upscaled Textures Epoch – 4K Maps *(Vish patch-M)* *(was PATCH-M)*
- **PATCH-R.MPQ** — New Skyboxes from WotLK HD DBC *(Bset)*  
- **PATCH-W.MPQ** — Cataclysm Water *(unknown modder)*
- **PATCH-X.MPQ** — Enhanced Sounds + Soundtracks from multiple WoW versions *(Vish patch-X)*

---

## Load Order & Naming Rules

The client loads `patch-<one character>.MPQ` — numbers first (`patch-2` … `patch-9`), then letters (`patch-A` … `patch-Z`). **Later letters win.** So the order here is:

`patch` → `2` → `3` → `4` → `5` → `A` → `B` → `C` → `D` → `E` → `F` → `G` → `M` → `N` → `R` → `W` → `X` → `Y`

---

## Useful Links

- [epochHD GitHub (Bset work)](https://github.com/TVBrowntown/epochHD)  
- [NexusMods – Faithful Upscaled Textures](https://mega.nz/folder/7bhHQLyC#th3RT29KOQk9SxhZMhLHEQ)  
- [NexusMods – Better Trees](https://www.nexusmods.com/worldofwarcraft/mods/881?tab=files)  
- [NexusMods – Push Fog Only](https://www.nexusmods.com/worldofwarcraft/mods/850?tab=files)  

---

## Credits & Thanks  

- **Bset**  
- **Vish**  
- **Jolander**  
- **Loriendal**  
- **OdysseyMods**  
- Various *unknown modders*  
- All players who test, report bugs, and contribute


**Summary:** This repack enhances **authentic Epoch visuals** with faithful upscales (armor, UI, maps, icons), subtle environment boosts (trees, skyboxes, fog clarity), while keeping the original game's aesthetic.

---

## 2. Add Vulkan via DXVK 2.7.1 (Windows)

Improve Direct3D rendering through Vulkan translations.

### **Steps:**

1. **Download DXVK 2.7.1**:  
   Download from GitHub:  
   [dxvk-2.7.1](https://github.com/doitsujin/dxvk/releases/download/v2.7.1/dxvk-2.7.1.tar.gz)

2. **Extract the Archive**:  
   Use 7-Zip or a similar tool to extract the `.tar.gz`.

3. **Copy Required DLLs**:  
   Navigate to `x32/` folder, and copy `d3d9.dll`  into the folder containing `Wow.exe` (your game executable).  


4. **Enable for NVIDIA GPUs**:  
   Follow this **video demo (GIF)** for setting Wow.exe highest potential graphics for NVIDIA GPUs.  
   ![Alt Text](https://i.imgur.com/zbFE6ZM.gif) 

---

## 3. Run graphical macros in games (you can also use this addon for almost the same result - [VanillaGraphicBoost](https://github.com/fleekx/VanillaGraphicBoost/) and skip below)

Macro 1 :
```
/Console environmentDetail 150
/Console groundEffectDensity 256
/Console groundEffectDist 600
/Console groundEffectFade 1277
/Console ffxGlow 1
/Console ffxspecial 1
/Console farclip 1600
/Console horizonFarclipScale 6
```

Macro 2 :
```
/Console skycloudlod 3
/Console waterDetail 3
/Console reflectionMode 3
/Console rippleDetail 3
/Console shadowmode 3
/Console shadowtexturesize 2048
/Console particleDensity 100
/Console ffxnetherworld 1
/Console ffxDeath 1
```

Macro 3 :
```
/Console sunshafts 2
/Console textureFilteringMode 5
/Console terrainMipLevel 0
/Console ssao 2
/Console ssaoblur 2
/Console weatherDensity 3
/Console gxmultisample 8
/Console violencelevel 5
/Console overridefarclip 1
```

Macro 4 :
```
/Console farclip 1600
/Console horizonfarclip 6226
/Console groundeffectdensity 256
/Console groundeffectdist 140
/Console smallcull 0
/Console characterAmbient 1
/Console extshadowquality 5
/Console componentEmissive 1
/Console SSAODistance 750
```

Macro 5 :
```
/Console specular 1
/Console componentSpecular 1
/Console lodObjectMinSize 1
/Console lodObjectCullSize 1
/Console lodObjectCullDist 200
/Console lodObjectFadeScale 300
/Console detailDoodadAlpha 100
```

Macro 6 :
```
/Console particleMTDensity 100
/Console showfootprints 1
/Console showfootprintparticles 1
/Console doodadLodDist 2000
/Console entityLodDist 100
/Console worldBaseMip 0
/console nameplateMaxDistance 41
```

In the epoch_live folder, in WTF -> "config.wtf" : add these lines only after you did in game previous 6 macros:
```
SET M2Faster "3"
SET gxTextureCacheSize "512"
SET objectFade "0"
SET screenshotQuality "10"
```

<img width="2557" height="1438" alt="image" src="https://github.com/user-attachments/assets/a9d97eba-5e3a-4c67-85af-c097ecee96b6" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/50ff72da-16e3-4a19-bbb7-488d414dfe2b" />
<img width="1713" height="877" alt="image" src="https://github.com/user-attachments/assets/cb1cfe76-331a-47bf-8b6c-a978c3a8a65e" />
<img width="1492" height="1051" alt="image" src="https://github.com/user-attachments/assets/c935cd51-03f2-47f8-be49-e50de31d882e" />
<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/45712dcb-d219-448b-9f9a-40fd745be2a4" />


