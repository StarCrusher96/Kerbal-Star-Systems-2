# Kerbal-Star-Systems-2 [2.0]

Kerbal Star Systems 2 serves as the successor to Galaxies Unbound, significantly expanding on its foundation. This ambitious mod elevates the Kerbal Space Program experience by offering a breathtaking representation of the stellar neighborhood surrounding Kerbol. KSS2 masterfully blends scientifically-based celestial systems with imaginative elements, creating a unique fusion of real-life astronomy and inventive fictional systems. Prepare to embark on an extraordinary journey through the cosmos!


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

## Minimum System Requirements
   * Memory: 16 GB RAM
   * Graphics: 1-2 GB VRAM
   * KSP: 1.12.x
   
   
## Installation 
### 1. Download KSS2    
  - You MUST delete previous KSS2 versions from GameData before installing KSS2 v2.0
  - GU is not compatable in the same game with KSS2. You will get Kopernicus warnings and it will not complete loading
  - Previous KSS2 versions (1.x) are not compatable in the same game with this version.  It will crash your game.
    
  - [GitHub](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/releases)
       - Download KSS2_Core.2.0.zip  Unzip the file into your GameData directory
       - Download the desired KSS2 system(s).  Unzip the file into your GameData directory.
	   - Download ContractPack.2.0.zip if you wish to use contracts. Unzip the file into your GameData directory.
       - Volumetric EVE is natively supported by KSS2.  Legacy EVE is not currently supported, but is being worked on.
  * With Core, SystemAethera, SystemAlphaCentauri, SystemLuhman16, ContractPack, the `KSS2`-folder should look like this.
	
		|- KSS2
			|- ContractPack
			|- Core
			|- SystemAethera
			|- SystemAlphaCentauri
			|- SystemLuhman16
			|- KSS2_License.md
			|- KSS2Settings.cfg


### 2. Dependencies
 * [**Kopernicus**](https://github.com/kopernicus/kopernicus/releases): REQUIRED. Download and install Kopernicus (v217 or later is required for the latest features in KSS2).
 * [**ModuleManager**](https://github.com/sarbian/ModuleManager) : REQUIRED. So many things depend on this.
 * [**NiakoUtils**](https://github.com/pkmniako/Kopernicus_VertexMitchellNetravaliHeightMap/releases): REQUIRED: Surface effects. Bundled alongside KSS2.  Put the 000_NiakoUtils directory in GameData.
 * [**Kopernicus Expansion-er**](https://github.com/VabienArt/KopernicusExpansion-Continueder/releases): Not strictly required but supports features like wormholes.
 * [KSP Community Fixes](https://github.com/KSPModdingLibs/KSPCommunityFixes/releases) Strongly recommended for the enhancements and many fixes it provides.
 
### 3. Visuals  
   * [**Volumetric EVE**](https://www.patreon.com/c/blackrack/posts/): For the new volumetric clouds, aurorae, geysers, etc. This is the Blackrack EVE and is currently not a free download.  Not required but without it, the experience is greatly reduced
   * [**Environmental Visual Enhancements Redux**](https://github.com/LGhassen/EnvironmentalVisualEnhancements/releases/): **NOT CURRENTLY SUPPORTED**
   * [**Scatterer**](https://github.com/LGhassen/Scatterer/releases): Atmospheric shaders for those that are unable to purchase the new EVE Volumetrics.
   * [**Parallax 2**](https://forum.kerbalspaceprogram.com/topic/209714-112x-parallax-pbr-terrain-and-surface-objects-202/): For the interesting ground scatter.  Note: Neither Parallax 1 nor Parallax Continued are supported
   * [**Singularity**](https://github.com/LGhassen/Singularity): For black hole visuals
   * [**INSTANTIATOR**](https://github.com/TheWhiteGuardian/Unofficial_INSTANTIATOR): For other interesting effects like pulsars. 
   * [**Distant Object Enhancement**](https://github.com/net-lisias-ksp/DistantObject): Makes objects realistically visible over large distances.
   * [**PlanetShine**](https://forum.kerbalspaceprogram.com/index.php?/topic/173138-112x-planetshine-0266-feb-22-2022/)
   * [**Deferred Rendering**](https://github.com/LGhassen/Deferred) - We recommend using this mod, but please be aware that Parallax 2.0 objects under 2 stars may appear significantly brighter when deferred lighting is enabled. You might want to adjust the settings to mitigate this issue.

   
### 4. KSS2 General Settings file 
It is adviced that you do not change any default settings unless you know what you are doing.  The KSS2 General Settings are located in the KSS2Settings.cfg file located in KSS2
   - SpaceAnomalies : NO setting change required. Requires Blueshift be installed and that Space Anomalies be enabled in Blueshift. You will need to find and either dock with or klaw the anomaly to make it owned. 
   - Exotics = True/False : Whether or not to enable some truely exotic things. These will be rare and will be challenging. Stock rockets and parts will not do it for you. They will present unique rewards though.
   - Wormholes = True/False : Whether or not to enable to wormhole network that connects the KSS2 systems. Take note that the network will be dynamic depending on which systems are installed.
   - HomeSwitch : Not currently implemented
   - HabitableWorlds : True/False : Whether or not to get Pandor around Novin, you must set the HabitableWorlds-setting to **True** in the KSS2Settings.cfg.
   - DistanceFactor : Not currently implemented
   - Rescale : Whether to use a 2.5x or 10x rescale factor. This setting needs Sigma Dimensions installed: https://github.com/Sigma88/Sigma-Dimensions
   - SunAsteroids = True/False : Whether to enable or disable asteroid belts around Kerbol
   - ExtraSolarAsteroids = True/False : Whether to enable or disable asteroid belts around the various KSS2 systems

### Known Issues
   - Parallax Continued is not supported and might cause issues. However we set up Parallax 2.0 support to prevent game-breaking events in case you want to try mixing KSS2 with Parallax Continued. 
   - Only Volumetric EVE is supported. legacy EVE is currently not supported. Support is planned. Use of legacy EVE with KSS2 will not cause issues though.

## Compatibility  
     
### Support Parts and Gameplay
   - [Sterling Systems](https://forum.kerbalspaceprogram.com/topic/219609-1125-sterling-systems-v0371-mar-02-2024/)
   - [Contract Configurator](https://github.com/KSP-RO/ContractConfigurator) KSS2 related contracts. V2.1.3 or greater.
   - [Kerbalism](https://forum.kerbalspaceprogram.com/index.php?/topic/190382-15-110-kerbalism-311/)
   - [Kerbal Health](https://forum.kerbalspaceprogram.com/index.php?/topic/155313-18-kerbal-health-163-2022-12-25/)
   - [Community Resource Pack](https://github.com/UmbraSpaceIndustries/CommunityResourcePack/releases)
   - [Rational Resources](https://forum.kerbalspaceprogram.com/index.php?/topic/184875-rational-resources-142-dec-25-2022/)
   - [Blueshift](https://github.com/Angel-125/Blueshift/releases) This is primarily a FTL mod, but it also provides Space Anomaly support. This is needed if you would like the various interesting space anomalies in KSS2 to be available. Enable Space Anomalies in the Blueshift in-game settings.
   - [WildBlueTools](https://github.com/Angel-125/WildBlueTools/releases) Primarily a collection of tools for the WildBlue mods, this provides interesting functionality for the space anomalies


### Planetmods - unless annotated, they are not known to be compatible but MAY be. Help us by testing and reporting your results.
   - Beyond Home
   - Corelian
   - ExtraSolar
   - GEP
   - GPP
   - Kcalbeloh
   - Lightlevels 
   - OPM (**Compatible**) Any OPM Parallax mod must be for Parallax 2
   - KSRSS (needs more testing)

### Not compatible
   - Principia
   - Galaxies Unbound (GU)
   - Previous versions of KSS2
   - Parallax 1
   - Parallax Continued
   - Komplexity (not compatible with the KSS2 contract system)
   - Mods not mentioned in this list have not been verified and might or might not work. Install at your own risk, there's no support for these.
   - Homeswitch and Galaxy mode are **NOT** currently supported


### Contracts
   - KSS2 has a custom contract system for Career Mode players.  [Contract Configurator](https://github.com/KSP-RO/ContractConfigurator) will need to be installed and you will need minimum v2.1.3. There are early and mid game contracts to help you staff up for the push to Interstellar and the main contracts will start to drop once you have fully upgraded the KSC. The contracts will steer you to the more interesting things.  The KSS2 contract system is not compatible with Komplexity.

## After launching the game (!important!)
### Checklist
  * You need Texture quality at its highest setting. Otherwise a few worlds may spawn as black orbs. 

### Maneuver Tool Bug
   * Source: [KSP Community Fixes](https://forum.kerbalspaceprogram.com/index.php?/topic/204002-18-112-kspcommunityfixes-bugfixes-and-qol-tweaks/) 
   
The KSP 1.12 maneuver planner tool will cause issues. It can cause stutter and freezes on scene load, when changing SOI, when timewarping far from Kerbol or when editing maneuver nodes, especially with Kopernicus modified systems. To solve this, you better disable it. 
KSS2 provides a patch when Community Fixes are installed to make sure this happens.

  ![screenshot2](https://raw.githubusercontent.com/KSPModdingLibs/KSPCommunityFixes/master/Screenshots/settings.gif)

## Support and Socials
  - [KSP Forum](https://forum.kerbalspaceprogram.com/topic/220876-111x-112x-kerbal-star-systems-2%E2%84%A2-dev)  
  - [Discord Server](https://discord.gg/acUttYPXd5)
  - [Youtube](https://www.youtube.com/channel/UCrEUo4-6hNuVxUPEKNv8EcA)  

### Obtaining Support
  - [Discord Server] (https://discord.com/channels/609404909464453120/609411550771675136/1123689293316112434) Remember: No GameData screenshot, no support

## Support Kerbal Star Systems 2!
Enjoy the mod? Consider donating to help me keep expanding and improving it. Your support truly makes a difference—thank you!

[<img src="https://villageatithaca.org/wp-content/uploads/2020/03/paypal-donate-button.png" width="20%"/>](https://www.paypal.com/donate/?hosted_button_id=7VBTXAZWDDQ4S)


[Kerbal Star Systems 2 ](https://forum.kerbalspaceprogram.com/topic/220876-111x-112x-kerbal-star-systems-2%E2%84%A2-dev)© 2025 by [StarCrusher96 ](https://forum.kerbalspaceprogram.com/profile/148335-starcrusher96/)is licensed under CC BY-NC-ND 4.0, with all textures, except as indicated, falling under an All Rights Reserved license.


