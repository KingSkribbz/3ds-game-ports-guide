# susbaconhairman skribbler's 3DS Game Ports Guide
!!! note Contact me
	If you need help, want to report an issue, or have suggestions, please contact me at [skribbler#1095](https://discord.com/users/961740410257039430) on Discord, or at [susbaconhairman@gmail.com](mailto:susbaconhairman@gmail.com).
!!! note Discord server
	Please join the Media Preservation Central server here: https://discord.gg/8mx5cpBZW2
---
###Prerequisites
!!! danger
	If your 3DS doesn't already have custom firmware (CFW), go to https://3ds.hacks.guide to add it. Make sure your CFW and device firmware are up-to-date.
!!! danger DSP firmware dump
	You will need to dump your DSP firmware for the audio to work on many games. To do that, turn on your console, and open up the Rosalina menu by pressing the Left shoulder + D-Pad down + Select buttons simultaneously. Select "Miscellaneous options", then "Dump DSP firmware". Press B to continue, and exit the Rosalina menu.
!!! warning
	Windows as your computer's OS is recommended, although you should be able to use any device for copying files to the card, as long as it's able to download things and has a (micro) SD card reader. You should have some form 7-zip installed for some of the files in this guide. For Windows, Mac, and Linux, you can get it at https://7-zip.org.
- If you want to request a game to be added to this list, the game must not be "easy" to install (like a pre-compiled CIA, such as DDLC-LÖVE), it has to have game files that need installation too. Also, to be clear, I do not make ports, I just write the guides on how to install them.
- In the downloads section, for each of the game's files, all "official" file downloads - that are made by the original provider of the files, listed after the installation instructions of each game - will be below the file's bold name. "Unofficial" mirrors - made by me - will be below the "official" file downloads. All file downloads will have a link description that is the site they are hosted on, like GitHub or Medafire. Mirrors made by me will have the site it's hosted on and the word "mirror" in it.
- All the files hosted by me on MEGA can be found here: https://mega.nz/folder/TvpH1LaR#HFoJX7d4xFeTl-JfX0qPPA
- All file sizes listed on this page are in -bytes (XB), not in -bibytes (XiB).
- Be sure to check out my other guides for the PS Vita - at [https://rentry.org/vita-game-ports-guide](https://rentry.org/vita-game-ports-guide)! - and the Wii U, which can be found here: [https://rentry.org/wii-u-game-ports-guide](https://rentry.org/wii-u-game-ports-guide).
---
!!! info Table of Contents
	[TOC2]
---
###Grand Theft Auto 3
![re3 3DS Port](https://u.cubeupload.com/susbaconhairman/re3.png)
!!! danger Compatibility
	This will only run on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL).
> **Game files, with 3DSX**
(721.06 MB) **re3.zip**
[**Mediafire**](https://www.mediafire.com/file/fj661ten51nayge/re3.zip/file)

[MEGA mirror](https://mega.nz/file/urgnRbxS#bxktKFRhr1y5pl4AgAU4qQ23Cx1ObAS6_ds870PM3RY)

> **CIA launcher**
(3.85 MB) **re3-txd.cia**
[**Discord CDN**](https://cdn.discordapp.com/attachments/830163628137119786/834462580445151262/re3-txd.cia) | [**Mediafire**](https://www.mediafire.com/file/3k69x5mo0jnkl3r/re3-txd.cia/file)

[MEGA mirror](https://mega.nz/file/a34TRbJb#ikirVFc41XEDRZHTAYysdlo_YCVMsltA56t1bWcX34A)
!!! info Installation
	Extract the ```re3.zip``` file after downloading it, and take the ```/re3/``` folder and put it in the ```/3ds/``` folder on your SD card. Then download the CIA launcher, put it on your SD card, and install it with FBI.
!!! note
	Links taken from https://www.youtube.com/watch?v=4QeESx6SqL4
---
###Grand Theft Auto: Vice City
![reVC 3DS Port](https://u.cubeupload.com/susbaconhairman/revc.png)
!!! danger Compatibility
	This will only run on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). The game is also very unstable, so expect low frames and crashes!
> **Game files, plus CIA and 3DSX launcher**
(1.3 GB) **miami.zip**
[**Mediafire**](https://www.mediafire.com/file/ac3z9n25nmht8sp/miami.zip/file)

[MEGA mirror](https://mega.nz/file/T6IznJ4R#ACe1GQkbc-5rh-DpGkgoTUBf55TW_yPn-twMryD_4-U)
!!! info Installation
	Extract the ```miami.zip``` file after downloading it from one of the links above. Then, copy the ```/miami/``` folder from the archive and copy it to your ```/3ds/``` folder on your 3DS's SD card. Go in the ```/miami/``` folder again and take the ```miami.cia``` file, put it on your SD card, and install it with FBI.
!!! note
	Thanks to "Nickkk aka the screw remover"/"spaceturd64" for giving me a better version of the game files
---
###Sonic Mania
![Sonic Mania](https://u.cubeupload.com/susbaconhairman/sonicmaniaplus.png)
!!! danger Compatibility
	This will only run on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL).
> **Game files**
(199.01 MB) **Data.zip**
[**MEGA**](https://mega.nz/file/qywESJqb#vNbJlelAyPr4juYVJn7nXdN76_CUYDUZmGYdqeBgbpY)

> **CIA and 3DSX launchers**
(2.28 MB) **SonicMania.cia**
[**MEGA**](https://mega.nz/file/PzxyyJgb#5pBwMJxA6v0k-0GKb4ErWF7ToXP1LjHTJtRgXdPrdAY)

(3.10 MB) **RetroEngine.3dsx**
[**MEGA**](https://mega.nz/file/SnhVnZgL#TweCtBZH9z-xcJEY-2wjn5BJAXypKkS9CFRn_f1ECks)
!!! info Installation
	Extract the ```Data.zip``` file, and copy the ```/Data/``` folder from the archive to the ```/3ds/SonicMania/``` directory on your SD card. Then, download the CIA launcher, put it on your SD, and install it with FBI. Download ```RetroEngine.3dsx```, and copy it to the ```/3ds/``` directory on your SD card.
!!! note
	Data.rsdk taken from https://www.reddit.com/r/VitaPiracy/comments/wpx92b/ and extracted by me, using this guide: https://www.youtube.com/watch?v=8oxISJxgBc4. CIA launcher and 3DSX provided by me, both of them built using this guide: https://github.com/SaturnSH2x2/RSDKv5-Decompilation/blob/3ds-main/GUIDE.md. Thanks to the people at the [Retro Engine Modding Server [REMS]](http://dc.railgun.works/retroengine) for helping me out with that.
---
###Half-Life
![Half-Life](https://u.cubeupload.com/susbaconhairman/xash3ds.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **Game files**
(572.47 MB) **HL+Extras.zip**
[**Google Drive**](https://drive.google.com/file/d/1OoBhMlan9eiZFfSThSQMCuxz1cU8Y-ew/view)

[MEGA mirror](https://mega.nz/file/jmpUxBpJ#Xh-c_aG-YO2-qGePs_had_RZ_FRnY8iQ7djncmUEoMg) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/xash3ds/HL%2BExtras.zip)

> **CIA and 3DSX launchers**
(1.68 MB) **Xash3DS.cia**
[**GitHub**](https://github.com/masterfeizz/Xash3DS/releases/download/v0.2/Xash3DS.cia)

[MEGA mirror](https://mega.nz/file/HrhEzYgT#3wW7z7h-aXKqpOD0JjvChNXp6_sAhJnXpg-yjHE9LwI) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/xash3ds/Xash3DS.cia)

(2.83 MB) **Xash3DS.3dsx**
[**GitHub**](https://github.com/masterfeizz/Xash3DS/releases/download/v0.2/Xash3DS.3dsx)

[MEGA mirror](https://mega.nz/file/i2pEQBIJ#-DSMttS6YNtVNFRYTwt4OjIWd8ZQ5m3V6dwUBpdBhls) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/xash3ds/Xash3DS.3dsx)
!!! info Installation
	Extract the ```HL+Extras.zip``` file that you downloaded from one of the links above. Navigate to ```/ux0/data/xash3d/```, and copy the valve folder to ```/xash3d/``` on your 3DS's SD card. Delete the ```config.cfg```, ```video.cfg```, and ```opengl.cfg``` files from the ```/xash3d/valve/``` folder of your SD card. Now, take the CIA launcher file you downloaded, put it on your SD, and install it with FBI. If you want, you can also take the 3DSX launcher and put it in the ```/3ds/``` folder on your SD.
!!! note
	Links taken from https://www.reddit.com/r/VitaPiracy/comments/92roaw/comment/e38021h/?utm_source=share&utm_medium=web2x&context=3 and https://github.com/masterfeizz/Xash3DS/
---
###Diablo
![Diablo 3DS port](https://u.cubeupload.com/susbaconhairman/49diablo.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **Game files**
(660.69 MB) **diasurgical.zip**
[**MEGA**](https://mega.nz/file/JHZV2YbC#EMMPmfNQ0uJs4Fa_yz4QzpdAZgGd-ATLwaAWyz-wxDM)

[MEGA mirror](https://mega.nz/file/CiJw0BAQ#QVODhiX1fQP7xvzGUckTSLiVG3rDLGGLEE6kN4SdvgE)

> **Additional files**
(55.8 MB) **fonts.mpq**
[**Github**](https://github.com/diasurgical/devilutionx-assets/releases/latest/download/fonts.mpq)

(38.4 MB) **pl.mpq**
[**Github**](https://github.com/diasurgical/devilutionx-assets/releases/latest/download/pl.mpq)

(33.1 MB) **ru.mpq**
[**Github**](https://github.com/diasurgical/devilutionx-assets/releases/latest/download/ru.mpq)

> **CIA and 3DSX launchers**
(12.9 MB) **devilutionx-3ds.cia**
[**Github**](https://github.com/diasurgical/devilutionX/releases/download/1.5.4/devilutionx-3ds.cia)

(13.6 MB) **devilutionx-3ds.3dsx**
[**Github**](https://github.com/diasurgical/devilutionX/releases/download/1.5.4/devilutionx-3ds.3dsx)

!!! info Installation
	Extract the ```diasurgical.zip``` file after downloading it, and go to the ```/diasurgical/``` folder. Copy the ```diabdat.mpq```, ```hellfire.mpq```, ```hfmonk.mpq```, ```hfmusic.mpq```, and ```hfvoice.mpq``` files to the ```/3ds/devilutionx/``` folder on your SD card. If you speak Chinese, Korean, or Japanese, then you need to download ```fonts.mpq```. If you speak Polish, then download ```pl.mpq```, and if you speak Russian, download ```ru.mpq```. Put it in with the rest of the files in ```/3ds/devilutionx/```. Finally, download the CIA launcher and install it with FBI, and/or download the 3DSX and put it in the ```/3ds/``` folder.
!!! note
	Links taken from [https://www.reddit.com/r/VitaPiracy/comments/r8txy4/](https://web.archive.org/web/20230426110040/https://www.reddit.com/r/VitaPiracy/comments/r8txy4/full_diablo_hellfire_data_files_download/) and https://github.com/diasurgical/
---
###3D Pinball - Space Cadet
![3D Pinball - Space Cadet](https://u.cubeupload.com/susbaconhairman/pinball.png)
> **Game files, plus CIA and 3DSX launcher**
(10.6 MB) **3DPinballSpaceCadet.zip**
[**Mega**](https://mega.nz/file/a7JwlR4J#8QLQCnUoKyFfk4r3Tves547ugsX3cYUTibnlrrKf03Y)
!!! info Installation
	Extract the ZIP file you downloaded from one of the links above. Go to the extracted archive and copy the ```SpaceCadetPinball.cia``` file to your SD card, then install it with FBI. Go back to the extracted archive's folder, and go to the ```/3ds/``` folder. Copy the ```SpaceCadetPinball.3dsx``` file, as well as the ```/SpaceCadetPinball/``` folder to ```/3ds/``` directory on your SD card.
!!! note
	File made by me, using this guide: [https://www.reddit.com/r/3DS/comments/yft0za/comment/iu5l571/](https://www.reddit.com/r/3DS/comments/yft0za/comment/iu5l571/), launcher CIA's taken from https://github.com/MaikelChan/SpaceCadetPinball/tree/3ds, some files taken from https://www.youtube.com/watch?v=Q2_xbMGelUU.
---
###PrBoom
![PrBoom](https://u.cubeupload.com/susbaconhairman/9fprboom.png)
> **DOOM WADs**
(5.01 MB) **Ultimate Doom, The.zip**
[**Archive.org**](https://archive.org/download/2020_03_22_DOOM/DOOM%20WADs/Ultimate%20Doom%2C%20The.zip)

[MEGA mirror](https://mega.nz/file/iuQy2YTZ#dBqGiUACavtkwW2Lmq3O4H7T_Wp4QzPbo1vUsy3xpzY) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/doom/Ultimate%20Doom%2C%20The.zip)

> **Important file**
(276.4 KB) **prboom.wad**
[**Github**](https://github.com/elhobbs/prboom3ds/releases/download/v0.7-alpha/prboom.wad)

[MEGA mirror](https://mega.nz/file/OjIyDRCD#ULsjt6vFGuKXvXgs7imRyeTKLauYteHusEn0uxRaxSw) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/prboom/prboom.wad)

> **CIA and 3DSX launchers**
(983.4 KB) **prboom3ds.cia**
[**Github**](https://github.com/elhobbs/prboom3ds/releases/download/v0.7-alpha/prboom3ds.cia)

[MEGA mirror](https://mega.nz/file/3qAlGbgJ#UQx5yujBfaPl2jT83CnFHN0T_Y5vX0tg6q2LC_4H2gg) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/prboom/prboom3ds.cia)

(932.8 KB) **prboom.3dsx**
[**Github**](https://github.com/elhobbs/prboom3ds/releases/download/v0.7-alpha/prboom3ds.3dsx)

[MEGA mirror](https://mega.nz/file/DnJh1Qhb#D52LyP8nv8xbmYibjrGonQGTziVfUaJ0MgLJmh_3ZOw) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/prboom/prboom3ds.3dsx)

(13.7 KB) **prboom.smdh**
[**Github**](https://github.com/elhobbs/prboom3ds/releases/download/v0.7-alpha/prboom3ds.smdh)

[MEGA mirror](https://mega.nz/file/7iAm2bpQ#i6uqwXfD4E09vqj41dNB6VxTkNssc3hOdUx5GFjes5w) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/prboom/prboom3ds.smdh)
!!! info Installation
	Extract the compressed DOOM WAD, then copy it to the ```/3ds/prboom3ds/``` folder on your SD card. Then, download ```prboom.wad```, and put it there too. Now, you need to either use the CIA or 3DSX launchers - or both - to play the game(s). For the CIA, download it, copy it to your SD card, and install it with FBI. For the 3DSX, download that as well as the SMDH file, copy them to the ```/3ds/``` folder on your SD card.
!!! info WADs
	You can always play other WADs, as long as they are based on the vanilla id Tech 1 engine.
!!! note
	Links taken from https://archive.org/details/2020_03_22_DOOM and https://github.com/elhobbs/prboom3ds/
---
###Duke Nukem 3D
![EDuke3D](https://u.cubeupload.com/susbaconhairman/eduke3d.png)
> **Game files, plus CIA and 3DSX launcher**
(19.26 MB) **DukeNukem3DS.rar**
[**Mediafire**](https://www.mediafire.com/file/x8qp5vl3ol2xop9/DukeNukem3DS.rar/file)

[MEGA mirror](https://mega.nz/file/SuoxRRxT#Yq0yVHNsgYM1in5BuH1S4XYYAwu0FjF40kDlcB7GNNg) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/duke/DukeNukem3DS.rar)
!!! info Installation
	Extract the ```DukeNuken3DS.rar file```, and navigate to ```/DukeNukem3DS/3ds```. Copy the ```/eduke3d/``` folder, as well as the ```eDukeVC.xml```, ```eDukeNW.xml```, ```eDuke3d.xml```, ```eDukeDC.xml```, and ```eDuke3d.3dsx``` files to the ```/3ds/``` folder on your console's SD card. Now, go back to the ```/DukeNukem3DS/``` folder, and copy the ```EDuke3D.cia``` file to your SD card, and install it with FBI.
!!! note
	Link taken from https://www.youtube.com/watch?v=canwEMYHQyo
---
###Raptor - Call of the Shadows
![Raptor3DS](https://u.cubeupload.com/susbaconhairman/raptor.png)
!!! danger Compatibility
	Only New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL) will have music. Other models will just have sound effects.
> **Game files**
(3.88 MB) **Raptor -  Call of the Shadows (1994).zip**
[**WowRoms**](https://wowroms.com/en/roms/dos/raptor-call-of-the-shadows-1994/149261.html)

[MEGA mirror](https://mega.nz/file/yzpmVSCA#CxSU_PoVEr8fGDieV13zLPVHmgwULcSgIeMKiAPz83M) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/raptor/Raptor%20-%20Call%20of%20the%20Shadows%20-%201994.zip)

> **CIA and 3DSX launchers**
(4.58 MB) **RAPTOR-3DS-SDL2-V0.9.1.zip**
[**Github**](https://github.com/RetroGamer02/raptor-consoles/releases/download/MultiSys-V1.0.3/RAPTOR-3DS-SDL2-V0.9.1.zip)
!!! info Installation
	Download the ```Raptor -  Call of the Shadows (1994).zip``` file, then extract it. Go to ```/Raptor -  Call of the Shadows (1994)/RaptorCa/```, and copy the ```FILE0002.GLB```, ```FILE0003.GLB```, and ```FILE0004.GLB``` files to ```/3ds/Raptor/``` on your 3DS's SD card. To launch the game, download ```RAPTOR-3DS-SDL2-V0.9.1.zip```, and extract it. Copy the ```RAPTOR-3DS-SDL2-V0.9.1.cia``` and ```RAPTOR-3DS-SDL2-V0.9.1.3dsx``` files to your SD card. Install the CIA with FBI, and put the 3DSX in your ```/3ds/``` folder.
!!! note
	Links taken from https://wowroms.com/en/roms/dos/raptor-call-of-the-shadows-1994/149261.html and https://github.com/RetroGamer02/raptor-consoles
---
###Sonic the Hedgehog 1 & 2
![Sonic the Hedgehog 1 & 2](https://u.cubeupload.com/susbaconhairman/532sonic.png)
!!! danger Compatibility
	This will only run on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL).
> **Game files and launchers**
(89.31 MB) **Sonic1and2.zip**
[**MEGA**](https://mega.nz/file/qrYW3SDZ#xj2-dl9CBQGMT3NkflHFSJaV4DOFVl2sqfjmgkBK9qc) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/sonic-1-2/Sonic1and2.zip)
!!! info Installation
	Download ```Sonic1and2.zip``` and extract the file. Next, copy the ```/Sonic1/``` and ```/Sonic2/``` folders from the archive and copy them to the ```/3ds/``` directory on your SD card. Now, copy the ```Sonic1.cia``` and ```Sonic2.cia``` files from the archive, copy them to your SD card, and install them with FBI. If one or more of the launchers didn't work for you, uninstall and remove the old launchers first. Then, copy the ```Sonic1_rev01.cia``` and ```Sonic2_rev01.cia``` files in the ```/rev01/``` folder from the ```Sonic1and2.zip``` archive to your SD card, and install them with FBI. Copy the ```Sonic1_rev01.3dsx``` and ```Sonic2_rev01.3dsx``` files from the same folder to the ```/3ds/Sonic1/``` and ```/3ds/Sonic2/``` directories on your SD card, respectively.
!!! note
	Game files and launchers packaged by me, with files taken from https://www.reddit.com/r/VitaPiracy/comments/l34yfi/comment/iyghn6y/?utm_source=share&utm_medium=web2x&context=3, and https://github.com/JeffRuLz/Sonic-1-2-2013-Decompilation.
---
###Sonic CD
![Sonic CD](https://u.cubeupload.com/susbaconhairman/soniccd.png)
> **Game files**
(75.62 MB) **Data.rsdk**
[**MEGA**](https://mega.nz/file/jmxUQQZR#fCHuW_0pEWkKbbdq8kS2lOHrmhSmdfJKnr8-0rzYEw8) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/sonic-cd/Data.rsdk)

> **CIA and 3DSX launchers**
(1.07 MB) **SonicCD.cia**
[**Github**](https://github.com/Voxel9/Sonic-CD-11-3DS-Redux/releases/download/v1.1.0/SonicCD.cia)

[MEGA mirror](https://mega.nz/file/jvBwXAJR#m0w_FKxL-shXVHEFq7n_aC2nJKPUhgkJnL4TZoySaw4) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/sonic-cd/SonicCD.cia)

(1.04 MB) **SonicCD.3dsx**
[**Github**](https://github.com/Voxel9/Sonic-CD-11-3DS-Redux/releases/download/v1.1.0/SonicCD.3dsx)

[MEGA mirror](https://mega.nz/file/q7YwHBLB#sZXVj52SR4oPED0YWstAznwdO_Hjbg6JPTbkKt__G-s) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/sonic-cd/SonicCD.3dsx)
!!! info Installation
	Download ```Data.rsdk``` and ```SonicCD.3dsx```, and copy them to the ```/3ds/SonicCD/``` folder on your 3DS's SD card. Then, download and copy ```SonicCD.cia``` to your SD card and install it with FBI.
!!! note
	Game file extracted by me, from https://apkpure.com/sonic-cd-classic/com.sega.soniccd.classic/download/2.0.1, while using instructions on how to extract it here: https://emuelec.discourse.group/t/sonic-1-2-and-cd-ports/33. CIA and 3DSX launchers are from https://github.com/Voxel9/Sonic-CD-11-3DS-Redux.
---
###PrBoom+
![PrBoom+](https://u.cubeupload.com/susbaconhairman/prboomplus.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower. If you have an old 3DS, you can use PrBoom, which a guide for can be found in this guide.
> **DOOM WADs**
(5.01 MB) **Ultimate Doom, The.zip**
[**Archive.org**](https://archive.org/download/2020_03_22_DOOM/DOOM%20WADs/Ultimate%20Doom%2C%20The.zip)

[MEGA mirror](https://mega.nz/file/iuQy2YTZ#dBqGiUACavtkwW2Lmq3O4H7T_Wp4QzPbo1vUsy3xpzY) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/doom/Ultimate%20Doom%2C%20The.zip)

> **Important files**
(30.03 MB) **PrBoom-Plus-3DS.zip**
[**Github**](https://github.com/Voxel9/PrBoom-Plus-3DS/releases/download/v1.0.0/PrBoom-Plus-3DS.zip)

> **CIA and 3DSX launchers**
(1.52 MB) **PrBoom-Plus.cia**
[**Github**](https://github.com/Voxel9/PrBoom-Plus-3DS/releases/download/v1.0.0/PrBoom-Plus.cia)

(2.22 MB) **PrBoom-Plus.3dsx**
[**Github**](https://github.com/Voxel9/PrBoom-Plus-3DS/releases/download/v1.0.0/PrBoom-Plus.3dsx)
!!! info Installation
		Download ```PrBoom-3DS-Plus.zip```, and open the archive. Copy the ```/etc/``` folder to the root of your console's SD card. Then, go to the ```/3ds/``` folder from the archive, and copy the ```/PrBoom-Plus/``` folder to ```/3ds/``` on your SD card. Download ```PrBoom-Plus.cia``` and copy it to your SD card. Next, acquire some DOOM WADs and place *one* base-game WAD (IWAD) into the ```/3ds/PrBoom-Plus/``` folder at a time. Then, put the rest of your WADs in ```/3ds/PrBoom-Plus/WADs/```. You can also use the ```/3ds/PrBoom-Plus/autoload/``` folder, which needs sub-folders with the names of each IWAD, such as ```doom.wad```, and one extra folder called ```doom-all```. Inside these sub-folders you can place *one* game expansion (PWAD) at a time for their respective IWADs (i.e. SIGIL or Lost Levels). For mods, you may place them in their respective folders too, alongside the expansions. Remember to use the ```/3ds/PrBoom-Plus/WADs/``` folder to store your other WADs for later. You must swap out files to play other games as of PrBoom+ 3DS v1.0.0. Go ahead and install the CIA with FBI.
!!! info WADs
	You can always play other WADs, as long as they are based on the vanilla id Tech 1 engine.
!!! note
	Links taken from https://archive.org/details/2020_03_22_DOOM and https://github.com/Voxel9/PrBoom-Plus-3DS. Thanks to "E'Mendo" for providing an updated installation description (with a few minor edits by me).
---
###Quake
![ctrQuake](https://u.cubeupload.com/susbaconhairman/quake.png)
> **CIA launcher**
(961 KB) **ctrQuake.cia**
[**GitHub**](https://github.com/masterfeizz/ctrQuake/releases/download/v0.8/ctrQuake.cia) | [**Mediafire**](https://www.mediafire.com/file/h338xd9j13m32fn/ctrQuake.cia/file)

[Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/quake/ctrQuake.cia)

> **Contains game files, also 3DSX launcher**
(22.24 MB) **ctrQuake.zip**
[**Mediafire**](https://www.mediafire.com/file/kitrxagyl87shvt/ctrQuake.zip/file)

[MEGA mirror](https://mega.nz/file/rrgHwApZ#70QUykuEC5f8eCOA1Cqrp8dK5lzRFCQ5sHnAW6kkSJk) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/quake/ctrQuake.zip)
!!! info Installation
	Download ```ctrQuake.cia```, copy it to your SD card, and install it with FBI. Then, download ```ctrQuake.zip```, extract it, go to the ```/ctrQuake/``` folder from the archive, and copy the ```/id1/``` folder to the ```/3ds/``` folder on your SD card. If you want to have the 3DSX launcher, go back to the ```/ctrQuake/``` folder from the archive, and copy the ```ctrQuake.3dsx``` and ```ctraQuake.smdh``` files to the ```/3ds/``` folder on your SD card.
!!! note
	CIA link taken from https://github.com/masterfeizz/ctrQuake. Thanks to "Nick aka the screw remover"/"spaceturd64" for providing the CIA mirror, as well as the games files.
---
###Quake 2
![Quake2CTR](https://u.cubeupload.com/susbaconhairman/quake2.png)
> **CIA launcher**
(52.1 MB) **Quake2CTR.cia**
[**Github**](https://github.com/masterfeizz/Quake2CTR/releases/download/v1.0/Quake2CTR.cia)

[Mediafire mirror](https://www.mediafire.com/file/3ami2uj6hqwnnou/Quake2CTR.cia/file) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/quake2/Quake2CTR.cia)

> **Game files**
(209.93 MB) **quake2.zip**
[**Mediafire**](https://www.mediafire.com/file/pahwsh5sc49fy5f/quake2.zip/file)

[MEGA mirror](https://mega.nz/file/TzxSDY4B#1rW9dq7ppBG-DZ4YSxuT6LxQ-tHnZQE8mrssDCROWgw) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/quake2/quake2.zip)
!!! info Installation
	Download ```Quake2CTR.cia```, copy it to your SD card, and install it with FBI. Then, download ```quake2.zip```, extract it, go to the extracted archive's folder, and copy the ```/quake2/``` folder to the ```/3ds/``` folder on your SD card.
!!! note
	CIA link taken from https://github.com/masterfeizz/Quake2CTR. Thanks to "Nick aka the screw remover"/"spaceturd64" for providing the CIA mirror, as well as the games files.
---
###Quake 3
![ioQuake3](https://u.cubeupload.com/susbaconhairman/quake3.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **CIA launcher**
(1.02 MB) **Quake3DS.cia**
[**Github**](https://github.com/masterfeizz/ioQuake3DS/releases/download/v1.2.0/Quake3DS.cia) | [**Mediafire**](https://www.mediafire.com/file/8nuwkgpnmutqvwe/ioQuake3DS.cia/file)

[Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/ioq3/Quake3DS.cia)

> **Game files**
(792.48 MB) **ioq3.zip**
[**Mediafire**](https://www.mediafire.com/file/ljoxceh0nba4sod/ioq3.zip/file)

[MEGA mirror](https://mega.nz/file/DrwziYxb#EBVcImoFqvBTSz1LR4hQ7rIOfWa_X8SLFV6hUMosQxA) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/ioq3/ioq3.zip)
!!! info Installation
	Download ```Quake3DS.cia```, copy it to your SD card, and install it with FBI. Then, download ```ioq3.zip```, extract it, go to the extracted archive's folder, and copy the ```/ioq3/``` folder to the root of your SD card.
!!! note
	CIA link taken from https://github.com/masterfeizz/ioQuake3DS. Thanks to "Nick aka the screw remover"/"spaceturd64" for providing the CIA mirror, as well as the games files.
---
###OpenArena
![OpenArena](https://u.cubeupload.com/susbaconhairman/openarena.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **CIA launcher**
(1.02 MB) **OpenArena.cia**
[**Github**](https://github.com/masterfeizz/ioQuake3DS/releases/download/v1.2.0/OpenArena.cia) | [**Mediafire**](https://www.mediafire.com/file/1l5b5zywqpzdsb3/OpenArena.cia/file)

[Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/openarena/OpenArena.cia)

> **Game files**
(394.8 MB) **openarena.zip**
[**Mediafire**](https://www.mediafire.com/file/u2jyre3xc1ec7y0/openarena.zip/file)

[MEGA mirror](https://mega.nz/file/mnJ3kLqI#pjbQyHZs2BD3JOe0vbGxA-sV3P3eiIA4doKvQDYfSt0) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/openarena/openarena.zip)
!!! info Installation
	Download ```OpenArena.cia```, copy it to your SD card, and install it with FBI. Then, download ```openarena.zip```, extract it, go to the extracted archive's folder, and copy the ```/openarena/``` folder to the root of your SD card.
!!! note
	CIA link taken from https://github.com/masterfeizz/ioQuake3DS. Thanks to "Nick aka the screw remover"/"spaceturd64" for providing the CIA mirror, as well as the games files.
---
###Sonic Robo Blast 2
![Sonic Robo Blast 2](https://u.cubeupload.com/susbaconhairman/sonicroboblast2.png)
!!! danger Compatibility
	This will only run on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL).
> **CIA and 3DSX launchers**
(2.89 MB) **srb2_3dsv1.1.3.zip**
[**Github**](https://github.com/derrekr/srb2_3ds/releases/download/v1.1.3/srb2_3dsv1.1.3.zip)

[MEGA mirror](https://mega.nz/file/Onp1RQzL#qH6oUpKgXWgvVVSqtYCzFEdk5EKBuqvxNCFeG3FtpJY) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/srb2/srb2_3dsv1.1.3.zip)

> **Game files**
(29.13 MB) **SRB2-v2122-assets.7z**
[**Github**](https://github.com/mazmazz/SRB2/releases/download/SRB2_assets/SRB2-v2122-assets.7z)

[MEGA mirror](https://mega.nz/file/u6gz3QJY#WJ7iQ8jSn3vIghssOJw7igK3ekzNmaHdkA9ue6qKgSc) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/srb2/SRB2-v2122-assets.7z)

(59.44 MB) **SRB2-v2122-optional-assets.7z**
[**Github**](https://github.com/mazmazz/SRB2/releases/download/SRB2_assets/SRB2-v2122-optional-assets.7z)

[MEGA mirror](https://mega.nz/file/eqpi1JjZ#xAdBp17jUqjagT5V5XBPzCHiBLFEBTf7RUTB2oPJs_o) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/srb2/SRB2-v2122-optional-assets.7z)
!!! info Installation
	Download ```srb2_3dsv1.1.3.zip```, extract it, and copy the ```srb2_3ds.3dsx``` to the ```/3ds/``` folder on your SD card. Then, copy the ```srb2_3ds.cia``` file to your SD card, and then install it with FBI. Now, download the ```SRB2-v2122-assets.7z``` and ```SRB2-v2122-optional-assets.7z``` files, extract them, and copy the files from both archives to the ```/3ds/srb2_3ds/``` folder on your SD card.
!!! note
	Links taken from https://github.com/derrekr/srb2_3ds and https://github.com/mazmazz/SRB2.
---
###Wolfenstein 3D
![Wolfenstein 3D](https://u.cubeupload.com/susbaconhairman/wolf.png)
> **3DSX launcher**
(2.24 MB) **wolf4sdl.3dsx**
[**Github**](https://github.com/hax0kartik/wolf4sdl-3ds/releases/download/v1.0/wolf4sdl.3dsx)

[MEGA mirror](https://mega.nz/file/mnImkbBb#Swz6HxV6VklkGbKJ1NOphYxdRSHetGzQQNW49R8IAGw) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/wolf/wolf4sdl.3dsx)

> **Game files**
(2.19 MB) **wolfenstein.zip**
[**MEGA**](https://mega.nz/file/a7g1EZhT#LEQ-9hiyKrikLJI6sK91MA-cumbUhmEhghLbXEhA4Dk) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/wolf/wolfenstein.zip)
!!! info Installation
	Download ```wolf4sdl.3dsx``` and copy it to the ```/3ds/wolf4sdl/``` folder on your SD card. Then, download ```wolfenstein.zip```, extract it, and copy all the .wl6 files from the archive to ```/3ds/wolf4sdl/wolf3d/``` on the SD card.
!!! note
	Game files from here: https://gog-games.to/game/wolfenstein_3d, packaged by me. 3DSX from https://github.com/hax0kartik/wolf4sdl-3ds.
---
###Tomb Raider
![Tomb Raider](https://u.cubeupload.com/susbaconhairman/raider.png)
> **CIA and 3DSX launchers**
(1.13 MB) **OpenLara.3dsx**
[**MEGA**](https://mega.nz/file/DvJzlA4R#eg84eGKElX_tbC7cKagJiroVYtMJLw0Oikq19vYcXko) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/raider/OpenLara.3dsx)

(1.59 MB) **OpenLara.cia**
[**MEGA**](https://mega.nz/file/TzhR0YZA#gQVPZXVYpAsrn92QLNGx7Vqoik6g55qtD5kbmldW5ow) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/raider/OpenLara.cia)

> **Game files**
(337.35 MB) **OpenLara.zip**
[**MEGA**](https://mega.nz/file/CmJXnSCJ#h57-WE-1zWen73DlE76E0y5GsExRjzYra8QHGXW6cA4) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/raider/OpenLara.zip)
!!! info Installation
	Download all the files listed above. Extract the archive, then copy the ```/OpenLara/``` folder from the archive and ```OpenLara.3dsx``` to the  ```/3ds/``` folder on your SD card. Next, copy ```OpenLara.cia``` to your SD card, and install it with FBI.
!!! note
	3DSX launcher taken from the archive for the 3DS release here: https://github.com/XProger/OpenLara. CIA and game files taken from https://www.youtube.com/watch?v=oKEn921rkRQ.
---
###Commander Keen
![Commander Keen](https://u.cubeupload.com/susbaconhairman/keen.png)
> **CIA and 3DSX launcher**
(1.03 MB) **OmniSpeak-3ds.V1.0.0.zip**
[**MEGA**](https://mega.nz/file/62QgAJLb#kPSYs5I03hmkS7kRy64yyQ1r_4Jj6fHxAmjdFFTBisQ) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/keen/OmniSpeak-3ds.V1.0.0.zip)

> **Game files**
(1.91 MB) **Commander Keen Files.zip**
[**MEGA**](https://mega.nz/file/amAikR6Q#D-pnqQBzWPxGA7bC3KcqqYgbpI2nq6wm8KyyNX8LS0U) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/keen/Commander%20Keen%20Files.zip)
!!! info Installation
	Download ```OmniSpeak-3ds.V1.0.0.zip```, extract it, and copy the ```OmniSpeak-3ds-V1.0.0.3dsx``` file to the ```/3ds/``` folder on your SD card, then copy the ```OmniSpeak-3ds-V1.0.0.cia``` file to your SD card, and install it with FBI. Next, download ```Commander Keen Files.zip``` and copy all 3 folders in the ```/Commander Keen Files/``` folder from the archive to ```/3ds/omnispeak/``` on your SD card.
!!! note
	Game files compiled by me, from these downloads: https://gamesnostalgia.com/game/commander-keen-4-secret-of-the-oracle, https://gamesnostalgia.com/game/commander-keen-5-the-armageddon-machine, https://gamesnostalgia.com/game/commander-keen-aliens-ate-my-babysitter. CIA and 3DSX launcher archive is from https://github.com/RetroGamer02/omnispeak-3ds.
---
###Blood
![Blood](https://u.cubeupload.com/susbaconhairman/blood.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **CIA and 3DSX launchers**
(1.20 MB) **nblood.cia**
[**Github**](https://github.com/MrHuu/jfblood-3ds/releases/download/v0.0.1/nblood.cia)

[MEGA mirror](https://mega.nz/file/eqJUGYLK#wmThKbJbNbJo6mgcr25eEIEvGoe9k7XNYxmHafmwaSQ) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/blood/nblood.cia)

(1.15 MB) **nblood.3dsx**
[**Github**](https://github.com/MrHuu/jfblood-3ds/releases/download/v0.0.1/nblood.3dsx)

[MEGA mirror](https://mega.nz/file/rnwlVLxD#igdGleXeMxUsKSEeC8pnW6jGaTodp-o9mELhc0YXSWk) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/blood/nblood.3dsx)

> **Game files**
(70.53 MB) **Blood Files.zip**
[**MEGA**](https://mega.nz/file/W7wBDQqT#kl_4lAoqmn_e6tUUIpWqWK091L0ycMKJzAyE2CiR0Ng) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/blood/Blood%20Files.zip)
!!! info Installation
	Download ```nblood.cia```, copy it to your SD card, and install it with FBI. Next, download ```nblood.3dsx``` and ```Blood Files.zip```. Extract the archive, then copy ```nblood.3dsx``` and the ```/NBlood/``` folder from the archive, to the ```/3ds/``` folder on your SD card.
!!! note
	CIA and 3DSX launchers from https://github.com/MrHuu/jfblood-3ds. Game files taken from here: https://gamesnostalgia.com/download/blood/2344.
---
###Heretic
![Heretic](https://u.cubeupload.com/susbaconhairman/heretic.png)
> **3DSX launcher**
(432.3 KB) **heretic3ds-v0.2a.zip**
[**Github**](https://github.com/elhobbs/heretic3ds/releases/download/v0.2a-alpha/heretic3ds-v0.2a.zip)

[MEGA mirror](https://mega.nz/file/KrY3wK4A#HVauf9h6VSirPcIJ0cy9ByMHT0gyQTSdXb2hadVfEVI) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/heretic/heretic3ds-v0.2a.zip)

> **Game files**
(10.58 MB) **heretic.wad**
[**MEGA**](https://mega.nz/file/HzA3wDYQ#d6rP8GBxiG_r1b36tuAUfHu8xcJerGJfQFlNbaranZY) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/heretic/heretic.wad)
!!! info Installation
	Download ```heretic3ds-v0.2a.zip``` and ```heretic.wad```. Extract the archive, then copy ```heretic.wad``` and both files from the archive to the ```/3ds/heretic3ds/``` folder on your SD card.
!!! note
	CIA and 3DSX launchers from https://github.com/elhobbs/heretic3ds. WAD file taken from https://gamesnostalgia.com/download/heretic/4735.
---
###Hexen II
![Hexen II](https://u.cubeupload.com/susbaconhairman/hexenii.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **CIA and 3DSX launchers**
(798.9 KB) **ctrHexenII.cia**
[**MEGA**](https://mega.nz/file/WmRBCChS#VbTPY3E2RyqYm4LtyExgs5iVzXR0cWW7K4o4Ylhi91g) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/hexen-ii/ctrHexenII.cia)

(722.2 KB) **ctrHexenII.3dsx**
[**MEGA**](https://mega.nz/file/fmwnEAQB#qy4HgHGnzHK9w5a9lHAyA2rEWNx1Wbj1myETsisaYQ4) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/hexen-ii/ctrHexenII.3dsx)

(13.7 KB) **ctrHexenII.smdh**
[**MEGA**](https://mega.nz/file/Hq41GCiB#SWpHesJf1oFQSS-AJLbuQN7ynDkzwx7NuVuw4IXjRTE) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/hexen-ii/ctrHexenII.smdh)

> **Game files**
(153.24 MB) **Hexen II.zip**
[**MEGA**](https://mega.nz/file/XuR3mRqL#Nf8BJSgGkBkMF-swGbsjFItNKwZu74towVr_9BAYBSA) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/hexen-ii/Hexen%20II.zip)
!!! info Installation
	Download ```ctrHexenII.3dsx``` and ```ctrHexenII.smdh```, then copy them to the ```/3ds/``` folder on your SD card. Next, download ```Hexen II.zip```, extract it, and copy the ```/portals/``` and ```/data1/``` folders to the root of the SD card. Finally, download ```ctrHexenII.cia```, copy it to the card, and install it with FBI.
!!! note
	CIA and 3DSX launchers from https://www.gamebrew.org/wiki/CtrHexenII_3DS. Game files taken from https://gamesnostalgia.com/download/hexen-ii/4138 and https://gamesnostalgia.com/game/hexen-ii-mission-pack-portal-of-praevus.
---
###Descent
![Descent](https://u.cubeupload.com/susbaconhairman/descent.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **3DSX launcher**
(1.75 MB) **d1x-3ds.3dsx**
[**Github**](https://github.com/RossMeikleham/DXX-3DS/releases/download/0.1/d1x-3ds.3dsx)

[MEGA mirror](https://mega.nz/file/nvAEyIpD#w3EtBcvm7ueTedzroO0n7FuxUs2C8EE_kdgUmXt8FXQ) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/descent/d1x-3ds.3dsx)

> **Game files**
(126.02 MB) **D1.zip**
[**MEGA**](https://mega.nz/file/HqQTiLSC#3skYXDQFa-cG9Q0RQi6WnujodcaEOpXxn0-UFywQjqY) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/descent/D1.zip)
!!! info Installation
	Download ```d1x-3ds.3dsx```, then copy it to the ```/3ds/``` folder on your SD card. Next, download ```D1.zip```, and copy the ```/D1/``` folder from the archive to the ```/3ds/``` directory on the SD card.
!!! note
	3DSX launchers from https://github.com/RossMeikleham/DXX-3DS. Game files taken from https://gog-games.to/game/descent
---
###Descent 2
![Descent 2](https://u.cubeupload.com/susbaconhairman/descent2.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **CIA and 3DSX launchers**
(2.15 MB) **d2x-3ds.3dsx**
[**Github**](https://github.com/RossMeikleham/DXX-3DS/releases/download/0.1/d2x-3ds.3dsx)

[MEGA mirror](https://mega.nz/file/Sj5B2Yib#ejSnQsXJs3kfLTbEZaZRSW9o2l9n_Xhlb_ucBl7zNvY) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/descent/d2x-3ds.3dsx)

> **Game files**
(41.64 MB) **D2.zip**
[**MEGA**](https://mega.nz/file/XmIk0ZiC#QH5uyb33cwjW8zZJz1QL2fW7wHeTTl3mkeb4jAQfitA) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/descent/D2.zip)
!!! info Installation
	Download ```d2x-3ds.3dsx```, then copy it to the ```/3ds/``` folder on your SD card. Next, download ```D2.zip```, extract it, and copy the ```/D2/``` folder from the archive to the ```/3ds/``` directory on the SD card.
!!! info
	This doesn't have sound for now, as I was unable to find audio files for it. I apologize for the inconvenience.
!!! note
	3DSX launchers from https://github.com/RossMeikleham/DXX-3DS. Game files taken from https://gog-games.to/game/descent_2.
---
###Kurok
![Kurok](https://u.cubeupload.com/susbaconhairman/9c0kurok.png)
> **Game files**
(28.69 MB) **Kurok3DS.zip**
[**Google Drive**](https://drive.google.com/file/d/0B1z--Zk0k2ccd3Q3cWZEZ1Z4eTA/view?usp=sharing&resourcekey=0-ALNNtQ5NC6bPVIX0zXBbuA)

[MEGA mirror](https://mega.nz/file/G7YXTZIY#5J1nQm-D4l7Oef0lpfMOcX2Triki7RfXJ5mHGOcaPUw) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/kurok/Kurok3DS.zip)
!!! info Installation
	**You must have [Quake](#quake) installed on your console first, before you will be able to play the game. This is a mod based off of Quake.** Download ```Kurok.zip```, extract it, and copy the ```Kurok.3dsx```, ```Kurok.smdh```, and ```Kurok.elf``` files to the ```/3ds/``` folder on your SD card. Then, copy the ```/Kurok/``` folder from the archive to the ```/3ds/ctrQuake/``` folder on your SD card.
!!! note
	Link taken from https://gbatemp.net/threads/release-kurok.462803/.
---
###Higurashi - When they Cry
![Higurashi](https://u.cubeupload.com/susbaconhairman/c6chigurashi.png)
> **Game files**
(370.0 MB) **Ch1_Onikakushi.zip**
[**MEGA**](https://mega.nz/file/3y5iDLyB#MfyAgYr44wEFkKbQ8aGR3fZ7sGQ6GhKNVz4NlHXr0cY) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/higurashi/Ch1_Onikakushi.zip)

(524.0 MB) **Ch2_Watanagashi.zip**
[**MEGA**](https://mega.nz/file/PyQBVDhI#3ppiuNZxfqvh1-fQBHF1ZTpZTQdn_JUgzsq-QQimeUo) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/higurashi/Ch2_Watanagashi.zip)

(467.0 MB) **Ch3_Tatarigoroshi.zip**
[**MEGA**](https://mega.nz/file/y65EQYyS#PiGxnzh3_wpysBN7yKmZ8Thc7pNrxqQywoiVeatc-bQ) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/higurashi/Ch3_Tatarigoroshi.zip)

(285.6 MB) **Ch4_Himatsubushi.zip**
[**MEGA**](https://mega.nz/file/n3hVEQxJ#vXmtWAkRc0hzJ97aYxvMm3xAqgZ3wT_kjI4yrWzDqZE) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/higurashi/Ch4_Himatsubushi.zip)

(531.6 MB) **Ch5_Meakashi.zip**
[**MEGA**](https://mega.nz/file/ingizS7S#eG4hhZLcTxeCoWmpUcob8rHfPd5LLIyzQyRsUrRLPp4) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/higurashi/Ch5_Meakashi.zip)

> **CIA and 3DSX launchers**
(1.38 MB) **Higurashi-3ds-v2.6.4.zip**
[**Github**](https://github.com/MyLegGuy/Higurashi-Vita/releases/download/v2.7/Higurashi-3ds-v2.6.4.zip)

[MEGA mirror](https://mega.nz/file/f6RhiaKb#C6Qy5OlkKQuk-j3lm07BwElVmzC_O6aud0JXnG4lK2Q) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/higurashi/Higurashi-3ds-v2.6.4.zip)
!!! info Installation
	Download ```Higurashi-3ds-v2.6.4.zip```, extract it, and copy the ```Higurashi.cia``` file from the ```/CIA/``` folder in the archive to the SD card, and install it with FBI. Then, go to the ```/3dsx/3ds/``` folder from the archive, and copy the ```/Higurashi/``` and ```/data/``` folders to the ```/3ds/``` directory on the SD card. Now, download all 5 of the game files, extract them, and copy the ```/StreamingAssets_ChX_(Chapter name).txt/``` folders from each archive to the ```/3ds/data/HIGURASHI/Games/``` directory on the SD card.
!!! note
	Game files compiled by me, following the guide on this site: [https://www.gamebrew.org/wiki/Higurashi_-_When_They_Cry_3DS_](https://www.gamebrew.org/wiki/Higurashi_-_When_They_Cry_3DS) and using the files from each chapter here: [Chapter 1](https://gog-games.to/game/higurashi_when_they_cry_hou_ch1_onikakushi), [Chapter 2](https://gog-games.to/game/higurashi_when_they_cry_hou_ch2_watanagashi), [Chapter 3](https://gog-games.to/game/higurashi_when_they_cry_hou_ch3_tatarigoroshi), [Chapter 4](https://gog-games.to/game/higurashi_when_they_cry_hou_ch4_himatsubushi), [Chapter 5](https://gog-games.to/game/higurashi_when_they_cry_hou_ch5_meakashi). CIA and 3DSX launchers taken from https://github.com/MyLegGuy/Higurashi-Vita/releases?page=3.
---
###Shadow Warrior
![Shadow Warrior](https://u.cubeupload.com/susbaconhairman/shadow.png)
!!! danger Mature Content
	This has lots of gore and strong sexual content, viewer discretion is advised!
> **Game files**
(110.3 MB) **Shadow Warrior.zip**
[**MEGA**](https://mega.nz/file/PmoGnLxa#wXfE-KaDNrhdJAPkVmTcBH6IcuxNsoHaTUfORIPxgok) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/warrior/Shadow%20Warrior.zip)

> **CIA launcher**
(1.38 MB) **jfsw.cia**
[**Github**](https://github.com/MrHuu/jfsw-3ds/releases/download/v0.0.3/jfsw.cia)

[MEGA mirror](https://mega.nz/file/3n41CYiA#6SCArERv4SlddyGOhZePoha8TXwXgxviH3_2FQt6B3g) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/warrior/jfsw.cia)
!!! info Installation
	Download ```Shadow Warrior.zip```, extract it, and copy the ```/JFSW/``` folder from the archive to the ```/3ds/``` folder on your SD card. Then, download ```jfsw.cia```, copy it to the SD card, and install it with FBI.
!!! note
	Game files compiled by me, using files from here: https://gog-games.to/game/shadow_warrior_classic_redux. CIA and 3DSX launchers taken from https://github.com/MrHuu/jfsw-3ds.
---
###Fallout
![Fallout](https://u.cubeupload.com/susbaconhairman/fallout.png)
> **Game files**
(512 MB) **Fallout.zip**
[**MEGA**](https://mega.nz/file/zihyTYaK#_7i7wLjFLUSiJkex_lH50bUO6RwtLdkcRmzPbiz1URY)

> **CIA and 3DSX launchers**
(1.72 MB) **fallout-ce.cia**
[**Github**](https://github.com/MrHuu/fallout1-ce-3ds/releases/download/v0.0.5/fallout-ce.cia)

(1.65 MB) **fallout-ce.3dsx**
[**Github**](https://github.com/MrHuu/fallout1-ce-3ds/releases/download/v0.0.5/fallout-ce.3dsx)
!!! info Installation
	Download ```Fallout.zip``` and ```fallout-ce.3dsx```, and copy the ```fallout-ce.3dsx``` file and extract the archive to the ```/3ds/fallout/``` directory on your SD card. Then, download ```fallout-ce.cia```, copy it to your SD card, and install it with FBI.
!!! note
	Thanks to Damsey diou for giving me the proper game files. CIA and 3DSX launchers taken from https://github.com/MrHuu/fallout1-ce-3ds.
---
###Plumbers Don't Wear Ties
![Plumbers Don't Wear Ties](https://u.cubeupload.com/susbaconhairman/plumber.png)
!!! danger Mature Content
	This game has lots of strong sexual content, viewer discretion is advised!
> **Game files**
(499.24 MB) **PlumbersDontWearTies.zip**
[**MEGA**](https://mega.nz/file/bqRRVZ5J#2xOp4d4fyFfjR2rJkdBLgmyn6LtziqPnDkADWaA_Bh0) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/plumber/PlumbersDontWearTies.zip)

> **CIA and 3DSX launchers**
(1.64 MB) **PlumbersDontWearTies-3ds-v0.2.zip**
[**Github**](https://github.com/MaikelChan/PlumbersDontWearTies-SDL/releases/download/v0.2-3ds/PlumbersDontWearTies-3ds-v0.2.zip)

[MEGA mirror](https://mega.nz/file/OqwRRSZT#BYFznFwfsn_fL-MZUJoL4Z3bK9PGE8OBurE3qLYllqM) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/plumber/PlumbersDontWearTies-3ds-v0.2.zip)
!!! info Installation
	Download ```PlumbersDontWearTies.zip```, extract the archive, and copy the ```/PlumbersDontWearTies/``` folder from the archive to the ```/3ds/``` directory on your SD card. Next, download ```PlumbersDontWearTies-3ds-v0.2.zip```, extract it, and copy the ```PlumbersDontWearTies-SDL.3dsx``` file to ```/3ds/``` on your SD card. Copy the ```PlumbersDontWearTies-SDL.cia``` file from the archive to the card, and install it with FBI.
!!! note
	Game files from https://archive.org/details/PLUMBER_201703, and compiled by me. CIA and 3DSX launchers taken from https://github.com/MaikelChan/PlumbersDontWearTies-SDL.
---
###Sonic Nexus
![Sonic Nexus](https://u.cubeupload.com/susbaconhairman/nexus.png)
!!! danger Compatibility
	This will run better on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL). You can use other models, but the game will run slower.
> **Game files**
(14.99 MB) **SonicNexus.zip**
[**MEGA**](https://mega.nz/file/TzJSzR4D#Ck3UWA90l0k_gbD02TLj4EboWw8KWu6wNvuW3jSguLM) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/nexus/SonicNexus.zip)
!!! info Installation
	Download ```SonicNexus.zip```, extract the archive, and copy the ```/SonicNexus/``` folder from the archive to the ```/3ds/``` directory on your SD card.
!!! note
	Game files from https://info.sonicretro.org/Sonic_Nexus#Downloads, and compiled by me. The instructions for that can be found here: https://www.gamebrew.org/wiki/Sonic_Nexus_3DS. CIA and 3DSX launchers taken from https://github.com/SnesFX/Sonic-Nexus-Decompilation.
---
###Super Mario War
![Super Mario War](https://u.cubeupload.com/susbaconhairman/mariowar.png)
!!! danger Compatibility
	This will only run on New 3DS models (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL).
> **Game files**
(24.61 MB) **SMW.zip**
[**MEGA**](https://mega.nz/file/2uYnWYQY#Md6qU8o3M1d3VJTrNh4MVWlA5qJZ1I-p_4l73SOok0w) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/mario-war/SMW.zip)
!!! info Installation
	Download ```SMW.zip```, extract the archive, and copy the ```/SMW/``` folder from the archive to the ```/3ds/``` directory on your SD card.
!!! note
	Game files from https://github.com/nop90/supermariowar-3ds.
---
###Cataclysm - Dark Days Ahead
![Cataclysm - Dark Days Ahead](https://u.cubeupload.com/susbaconhairman/cataclysm.png)
> **Game files**
(7.4 MB) **cdda_file.zip**
[**Github**](https://github.com/itsmariush/Cataclysm-DDA_3DS/releases/download/3ds_prev_v1/cdda_file.zip)

[MEGA mirror](https://mega.nz/file/7y5x3ZSA#0whYZFKbHz9Aw-u218t_79WaLAVtdbApNVdmi7zQ6KE) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/cdda/cdda_file.zip)

> **3DSX launcher**
(14.95 MB) **cdda.3dsx**
[**Github**](https://github.com/itsmariush/Cataclysm-DDA_3DS/releases/download/3ds_prev_v1/cdda.3dsx)

[MEGA mirror](https://mega.nz/file/ey5SET7a#85FlHOwGmdIdcTawbH8gZaXhN4CdnjeKwPXnXPySgCI) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/cdda/cdda.3dsx)
!!! info Installation
	Download ```cdda_file.zip```, extract the archive, and copy the ```/data/``` and ```/cataclysm-dda/``` folders from the archive to the root of your SD card. Then, download ```cdda.3dsx``` and copy it to the ```/3ds/``` folder on the SD card.
!!! note
	Game files from https://github.com/itsmariush/Cataclysm-DDA_3DS.
---
###The Legend of Sword and Fairy
![The Legend of Sword and Fairy](https://u.cubeupload.com/susbaconhairman/sdlpal.png)
> **Game files**
(247.56 MB) **sdlpal.zip**
[**MEGA**](https://mega.nz/file/Drx2lYJJ#IJmKJIPHzsWW9nuIpNeWkCRUg9PhL9WLDSXTwtHVT68) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/sdlpal/sdlpal.zip)

(1.2 KB) **config.zip**
[**MEGA**](https://mega.nz/file/KyQmQYTY#KMbYTJAERbp1ZRvOl_PO0_mKKhivoIsPs-3i8eakcIs) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/sdlpal/config.zip)

> **CIA and 3DSX launchers**
(2.0 MB) **classic.cia**
[**Github**](https://github.com/zephray/sdlpal-old/releases/download/v1.1/classic.cia)

[MEGA mirror](https://mega.nz/file/f7ZABJxK#_Weftn1DUMmqJGS663RNndD0WHvsb5jTgMmsdgpGddo) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/sdlpal/classic.cia)

(2.6 MB) **classic.3dsx**
[**Github**](https://github.com/zephray/sdlpal-old/releases/download/v1.1/classic.3dsx)

[MEGA mirror](https://mega.nz/file/u6ZSRSII#DxQ0J14zXCsYkuCefK0LiufAJmhd8zhE1szzNAWPWwQ) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/sdlpal/classic.3dsx)
!!! info Installation
	Download ```sdlpal.zip```, extract the archive, and copy the ```/sdlpal/``` folder from the archive to the ```/3ds/``` directory on your SD card. Now, download ```config.zip```, and extract it. If you are on a new 3DS (New Nintendo 3DS, New Nintendo 3DS XL/LL, New Nintendo 2DS XL/LL), then copy the ```sdlpal.cfg``` file in the ```/n3ds/``` folder from the archive, to the ```/3ds/sdlpal/``` directory on your SD card, then turn on the CPU+L2 boost in the Luma configuration menu, by holding Select while powering on the system. If you are on an old 3DS (Nintendo 3DS, Nintendo 3DS XL/LL, Nintendo 2DS), then copy the ```sdlpal.cfg``` file in the ```/o3ds/``` folder from the archive, to the ```/3ds/sdlpal/``` directory on your SD card. Next, download ```classic.cia``` and ```classic.3dsx```, and copy the CIA to anywhere on your card, and the 3DSX to the ```/3ds/``` folder.
!!! note
	Game files from https://archive.org/details/pal1_1995, and compiled by me, with instructions from here: https://www.gamebrew.org/wiki/SDLPAL_3DS, while using the English patch for the game: https://www.romhacking.net/translations/2441. CIA and 3DSX launchers taken from https://github.com/zephray/sdlpal-old.
---
###C-Dogs
![C-Dogs](https://u.cubeupload.com/susbaconhairman/cdogs.png)
> **Game files**
(3.25 MB) **C-Dogs3DS.zip**
[**MEGA**](https://mega.nz/file/muRRFDZT#JOi3AHYyVuK1D5bhkXTq8_matIELT9ThJa2Ok3e3yu8) | [**Archive.org**](https://archive.org/download/game-ports-guide-files-backup/3ds/c-dogs/C-Dogs3DS.zip)
!!! info Installation
	Download ```C-Dogs3DS.zip```, extract the archive, and copy the ```/C-Dogs3DS/``` folder from the archive to the ```/3ds/``` directory on your SD card.
!!! note
	Game files from https://github.com/MrHuu/cdogs-3ds and [http://www.orcsoftware.com/~ronny/cpns.zip](http://web.archive.org/web/20060108092027/http://www.orcsoftware.com:80/~ronny/cpns.zip)
---
###Blasphemer
![Blasphemer](https://u.cubeupload.com/susbaconhairman/blasphemer.png)
> **Game files**
(8.18 MB) **heretic3d.zip**
[**GBAtemp**](https://gbatemp.net/attachments/heretic3d-zip.115073/)

[MEGA mirror](https://mega.nz/file/mi4xxIiQ#plS9DK_QBEIpvG03TYf_H1sNg3LPvIfwK01QlT_oYgY) | [Archive.org mirror](https://archive.org/download/game-ports-guide-files-backup/3ds/blasphemer/heretic3d.zip)
!!! info Installation
	Download ```heretic3d.zip```, extract the archive, and copy the ```/heretic3d/``` folder from the archive to the ```/3ds/``` directory on your SD card.
!!! note
	Game files from https://gbatemp.net/threads/release-blasphemer-homebrew-based-on-heretic-1-open-source-game-content.497208/.
---
###Lemmings
![Lemmings](https://u.cubeupload.com/susbaconhairman/lemmings.png)
> **Game files**
(2.12 MB) **lemmings.zip**
[**MEGA**](https://mega.nz/file/unojFbiZ#vxjK2AgmlyIhg0zdknJmGXZSKBR2z7ZKhu9NWwWUoiY)
!!! info Installation
	Download ```lemmings.zip```, extract the archive, and copy the ```/lemmings/``` folder from the archive to the ```/3ds/``` directory on your SD card. Then, copy the ```lemmings.cia``` file from the archive to your SD card, and install it with FBI.
!!! note
	Game files from https://github.com/esoteric-programmer/lemmings_3ds, https://www.myabandonware.com/game/lemmings-16x, https://www.myabandonware.com/game/oh-no-more-lemmings-18b, https://www.myabandonware.com/game/xmas-lemmings-4b4, https://www.myabandonware.com/game/xmas-lemmings-3vr, https://www.myabandonware.com/game/holiday-lemmings-1tq, and https://www.myabandonware.com/game/holiday-lemmings-7r9.
---
###Stuff that might come soon
dethrace-3ds https://github.com/MrHuu/dethrace-3ds

**Things I might have to redo:**
Descent 2: https://github.com/RossMeikleham/DXX-3DS (I need to find the audio files)
