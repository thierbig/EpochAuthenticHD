#  Pstar Authentic Repack – Faithful / Curated, Enhanced + DXVK

A carefully selected **Epoch Graphics Collection** with essential upscaling patches, subtle world upgrades, and Vulkan support via DXVK 2.7.1 for improved graphics performance.

Keep the authentic Classic WoW look, just a little more crisper!

Download here: 

Extract the .mpq into the Data folder and the Icons into the Interface folder.

## 1. Epoch / WotLK MPQ Setup (Just for reading information)

---

## Core Game Files  
⚠️ **Do not change or delete these!**

- **COMMON.MPQ**  
- **COMMON-2.MPQ**  
- **EXPANSION-2.MPQ**  
- **LICHKING.MPQ**  
- **PATCH.MPQ**  
- **PATCH-2.MPQ**  
- **PATCH-3.MPQ**  
- **PATCH-A.MPQ**  
- **PATCH-B.MPQ**  
- **PATCH-Y.MPQ**  
- **PATCH-Z.MPQ**

---

## Custom MPQs Added

- **PATCH-4.MPQ** — Vanilla NPC texture upscale 2x *(unknown modder)*  
- **PATCH-5.MPQ** — Vanilla armor items texture upscale 2x *(unknown modder)*  
- **PATCH-6.MPQ** — Faithful Upscaled Textures Epoch *(Vish patch-D)*  
- **PATCH-7.MPQ** — Faithful Upscaled Textures Epoch – Creatures *(Vish patch-O)*  
- **PATCH-C.MPQ** — **HD Character Models from WotLK HD**, maintained by *Loriendal*.  
- **PATCH-F.MPQ** — Better Trees *(OdysseyMods)*  
- **PATCH-R.MPQ** — New Skyboxes from WotLK HD DBC *(Bset)*  
- **PATCH-S.MPQ** — New Skyboxes from WotLK HD *(Bset)*  
- **PATCH-W.MPQ** — Cataclysm Water *(unknown modder)*  
- **PATCH-X.MPQ** — Epoch - Old World Music Rescore Compatibility (Vish patchx)*
- **PATCH-I.MPQ** — Faithful Upscaled Textures Epoch – Spells/Items Icons *(Vish patch-I)*  
- **PATCH-M.MPQ** — Faithful Upscaled Textures Epoch – 4K Maps *(Vish patch-M)*  

---

## Useful Links

- [epochHD GitHub (Bset work)](https://github.com/TVBrowntown/epochHD)  
- [NexusMods – Faithful Upscaled Textures](https://www.nexusmods.com/worldofwarcraft/mods/884?tab=posts)  
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
   `https://github.com/doitsujin/dxvk/releases/download/v2.7.1/dxvk-2.7.1.tar.gz`

2. **Extract the Archive**:  
   Use 7-Zip or a similar tool to extract the `.tar.gz`.

3. **Copy Required DLLs**:  
   Navigate to `x32/` folder, and copy `d3d9.dll`  into the folder containing `Ascension.exe` (your game executable).  


4. **Enable for NVIDIA GPUs**:  
   Follow this **video demo (GIF)**[Gif](https://cdn.discordapp.com/attachments/1411180795405799549/1413087551970873405/Recording_2025-09-04_110412.mp4?ex=68bd4ad6&is=68bbf956&hm=c006b763c52119ba3f3309dfb510c3dc34b54bfd83ad1bea99240919e56110c6&) for setting the device override or preferences for NVIDIA GPUs.  

---

## 3. Run graphical macros in games:

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
