# Kerbal-Star-Systems-2 [1.0.3.1]

Kerbal Star Systems 2 is the successor to Galaxies Unbound and builds greatly upon the work in Galaxies Unbound.  KSS2 takes KSP to yet another new level by bringing you a stunning interpretation of the stellar neighbourhood near Kerbol.


## Overview
   - [**System Requirements**](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#minimum-system-requirements)
   - [**Installation**](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#installation)
      - [1. Download KSS2](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#1-download-kss2)
      - [2. Dependencies](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#2-dependencies)
      - [3. Visuals](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#3-visuals)
      - [4. KSS2 General Settings file](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#4-kss2-general-settings-file)
   - [**Compatibility**](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#compatibility)
      - [Support Visuals](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#support-visuals)
      - [Support Parts & Gameplay](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#support-parts-and-gameplay)
      - [Planetmods](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#planetmods)
      - [Not Compatible](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#not-compatible)
      - [Contracts](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#contracts)
   - [**After launching the game**](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#after-launching-the-game-important)
      - [Checklist](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#checklist)
      - [Maneuver Tool Bug](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#maneuver-tool-bug)
   - [**Home Switch and Galaxy mode**](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#home-switch-and-galaxy-mode)
   - [**Support and Socials**](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/blob/main/README.md#support-and-socials)


##


## Minimum System Requirements
   * Memory: 8-16 GB RAM
   * Graphics: 1-2 GB VRAM
   * KSP: 1.12.x
   
   
## Installation 
### 1. Download KSS2    
  - Delete previous KSS2 versions from GameData before installing. Merging with old files will not ensure the mod to work properly.
  - [GitHub](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/releases)
  - For the 1.0.3.1 release, you need to download the KSS2_Core.1.0.3.1 and SystemAethera.1.0.3.1 files. Delete the current KSS2 directory from GameData and install these. 
  - GU is not compatable in the same game with KSS2. You will get Kopernicus warnings and it will not complete loading
       - Download KSS2_Core.  Unzip the file and copy the KSS2 directory into your GameData directory
       - Download the desired KSS2 system.  Unzip the file and also copy the KSS2 directory into your GameData directory.
       - Volumetric EVE is natively supported by KSS2.  Legacy EVE is not currently supported, but is being worked on.
  * The `KSS2`-folder should look like this.


![KSS2_folder](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/assets/55005980/fcd318a4-5b14-4051-946e-76c549279300)



### 2. Dependencies
 * [**Kopernicus**](https://github.com/kopernicus/kopernicus/releases): Download and install Kopernicus (v204 or later is required for the latest features in KSS2).
 
### 3. Visuals  
   * [**Volumetric EVE**](https://www.patreon.com/posts/true-volumetric-77198227): For volumetric clouds, aurorae, geysers, etc. This is currently not a free download.  Not required but without it, the experience is greatly reduced
       - If you choose to not purchase the Volumetric EVE, then the two below downloads will give a reduced - though better than nothing experience
   * [**Environmental Visual Enhancements Redux**](https://github.com/LGhassen/EnvironmentalVisualEnhancements/releases/): **NOT CURRENTLY SUPPORTED** For those that are unable to purchase the new EVE Volumetrics. Many of the more immersive features will not be available. **SUPPORT COMING SOON.**
   * [**Scatterer**](https://github.com/LGhassen/Scatterer/releases): Atmospheric shaders for those that are unable to purchase the new EVE Volumetrics.
   * [**Parallax2**](https://forum.kerbalspaceprogram.com/topic/209714-112x-parallax-pbr-terrain-and-surface-objects-202/): For the interesting ground scatter.  Note: Parallax 1 is not supported
   * [**NiftyNebulae**](https://github.com/RJVB09/NiftyNebulae/releases): For dust rings, nebulae, etc.
   
### 4. KSS2 General Settings file 
   - Advise that you do not change any default settings unless you know what you are doing
   - GravityFix = True/False : Lowers Black holes', neutron stars' gravity. (will come in handy later)
   - GroundScatterDistance = x : Choose between 2 - 4 - 6 - 8 - 10 - 12 (groundscatters rendered over x distance in km)
   - RemoveLenseDirt = True/False : Removes lense dirt from all stars.
   - SunAsteroidBelts = True/False : Use this to add asteroidbelts around the Sun.
   - ExtraSolarAsteroids = True/False : Use this to add asteroidbelts around other stars.
   - Scale = x : Rescale * 1 - 2.5 - 10 (!needs [SigmaDimensions](https://github.com/Sigma88/Sigma-Dimensions/releases)) Note: This does not currently work properly. Do not use rescale.

### Known Issues
   - Rescale does not currently work correctly. It is a known issue and will be corrected in the next major release of KSS2

## Compatibility  
### Support Visuals
   -  [**Volumetric EVE**](https://www.patreon.com/posts/true-volumetric-77198227)
   - [Environmental Visual Enhancements Redux](https://forum.kerbalspaceprogram.com/index.php?/topic/196411-19-112x-eve-redux-performance-enhanced-eve-maintenance-v11171-09092022/)
   - [Scatterer](https://forum.kerbalspaceprogram.com/index.php?/topic/103963-wip19x-112x-scatterer-atmospheric-scattering-00838-14082022-scattering-improvements-in-game-atmo-generation-and-multi-sun-support/#:~:text=Scatterer%20is%20a%20graphical%20mod,Atmospheric%20scattering)
   - [Parallax2](https://forum.kerbalspaceprogram.com/index.php?/topic/209714-112x-parallax-pbr-terrain-and-surface-objects-202/) (Parallax Stock Textures are required)
   - [Instantiator](https://forum.kerbalspaceprogram.com/index.php?/topic/168992-13x-instantiator/)
   - [Distant Object Enhancement](https://forum.kerbalspaceprogram.com/index.php?/topic/189759-18-112x-distant-object-enhancement-continued-v2031-29-september-2021/)
   - [Kopernicus Expansion-er](https://forum.kerbalspaceprogram.com/topic/195844-110-112-kopernicus-expansion-continued-er/) Footprints and a few other interesting things
   - [NiftyNebulae](https://github.com/RJVB09/NiftyNebulae/releases)
     
### Support Parts and Gameplay
   - [Sterling Systems](https://forum.kerbalspaceprogram.com/topic/219609-1125-sterling-systems-v0371-mar-02-2024/)
   - [Contract Configurator](https://forum.kerbalspaceprogram.com/topic/91625-1101-contract-configurator-v1305-2020-10-05/page/208/) KSS2 related contracts. V2.1.3 or greater.
   - [Kerbalism](https://forum.kerbalspaceprogram.com/index.php?/topic/190382-15-110-kerbalism-311/)
   - [Rational Resources](https://forum.kerbalspaceprogram.com/index.php?/topic/184875-rational-resources-142-dec-25-2022/)
   - [KSP Community Fixes](https://forum.kerbalspaceprogram.com/index.php?/topic/204002-18-112-kspcommunityfixes-bugfixes-and-qol-tweaks/)

### Support (future)
   - [Kerbal Health](https://forum.kerbalspaceprogram.com/index.php?/topic/155313-18-kerbal-health-163-2022-12-25/)
   - [PlanetShine](https://forum.kerbalspaceprogram.com/index.php?/topic/173138-112x-planetshine-0266-feb-22-2022/)
   - [Singularity](https://github.com/LGhassen/Singularity/releases)

### Planetmods - unless annotated, they are not known to be compatible but MAY be. Help us by testing and reporting your results.
   - Beyond Home
   - Corelian
   - ExtraSolar
   - GEP
   - GPP
   - Kcalbeloh (**Compatible**) default settings only. Remove 000_NiakoUtils directory and set **DisableSkybox = True** in Kcalbeloh System Settings.cfg
   - Lightlevels 
   - OPM (**Compatible**)
   - KSRSS

### Not compatible
   - Principia
   - Galaxies Unbound
   - legacy EVE
   - OPM Parallax mods
   - Parallax 1
   - Parallax Continued
   - Mods not mentioned in this list have not been verified and might or might not work. Install at your own risk, there's no support for these.
   - Homeswitch and Galaxy mode are **NOT** currently supported

### Contracts
   - KSS2 has a custom contract system for Career Mode players.  [Contract Configurator](https://forum.kerbalspaceprogram.com/topic/91625-1101-contract-configurator-v1305-2020-10-05/page/208/) will need to be installed and you will need minimum v2.1.3. There are early and mid game contracts to help you staff up for the push to Interstellar and the main contracts will start to drop once you have fully upgraded the KSC. The contracts will steer you to the more interesting things.

## After launching the game (!important!)
### Checklist
  * You need Texture quality at its highest setting. Otherwise a few worlds may spawn as black orbs. 

### Maneuver Tool Bug
   * Source: [KSP Community Fixes](https://forum.kerbalspaceprogram.com/index.php?/topic/204002-18-112-kspcommunityfixes-bugfixes-and-qol-tweaks/) 
   
The KSP 1.12 maneuver planner tool will cause issues. It can cause stutter and freezes on scene load, when changing SOI, when timewarping far from Kerbol or when editing maneuver nodes, especially with Kopernicus modified systems. To solve this, you better disable it. 
KSS2 provides a patch when Community Fixes are installed to make sure this happens.

  ![screenshot2](https://raw.githubusercontent.com/KSPModdingLibs/KSPCommunityFixes/master/Screenshots/settings.gif)


## Home Switch and Galaxy mode
  Neither Home Switch nor Galaxy mode are supported in KSS2 at this time. 

## Chart of the Stars

TBA


## Support and Socials
  - [KSP Forum](https://forum.kerbalspaceprogram.com/topic/220876-111x-112x-kerbal-star-systems-2%E2%84%A2-dev)  
  - [Discord Server](https://discord.gg/acUttYPXd5)
  - [Youtube](https://www.youtube.com/channel/UCrEUo4-6hNuVxUPEKNv8EcA)  


Kerbal Star Systems 2 © 2024 by StarCrusher96 is licensed under CC BY-NC-ND 4.0.
