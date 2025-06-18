# Kerbal-Star-Systems-2 [3.0.1]

Kerbal Star Systems 2 (KSS2) is a large-scale interstellar mod for Kerbal Space Program, expanding the game far beyond the Kerbol system with a collection of detailed star systems, ranging from realistic exoplanets to fully fictional cosmic wonders.

As the spiritual successor to kerbal Star Systems 1 and Galaxies Unbound, KSS2 brings both scientific grounding and creative worldbuilding together in one of the most ambitious projects the KSP modding scene has seen. Its reputation has sparked plenty of discussion, but few deny the scale and depth it brings to the game.

Compatibility information and installation instructions can be found below.

## Key Features:
- **Realistic Stellar Systems**: Features a mixture of real-life astronomy and fictional systems.
- **Increased Scale**: Expands on previous planetary packs, giving players more environments to explore.
- **Dynamic Gameplay**: With its extensive system additions, the mod transforms the KSP experience into a more complex and immersive space simulation.

---

## System Requirements:
- **Memory**: 16 GB RAM
- **Graphics**: 1-2 GB VRAM
- **KSP Version**: 1.12.x

---
     
## Installation Guide:
### 1. Downloading KSS2:
Before installing **KSS2 v3.0**, ensure that previous versions of KSS2 are removed from your GameData directory. This version is **incompatible** with *Galaxies Unbound* (GU) and older KSS2 versions (1.x), and may cause the game to crash or fail to load.

**Steps to Install**:
1. **Download KSS2** from [GitHub](https://github.com/StarCrusher96/Kerbal-Star-Systems-2/releases).
2. Extract the following into your **GameData** directory:
   - KSS2_Core.2.0.zip
   - Desired KSS2 system(s) (e.g., SystemAethera, SystemAlphaCentauri, SystemLuhman16, )
   - **Optional**: If you want to use contracts, download and extract *ContractPack.2.0.zip*.
3. **Volumetric EVE** is supported by KSS2 for enhanced visuals (Legacy EVE is not compatible).

Your **KSS2** folder should look like this:
	
		|- KSS2
			|- ContractPack
			|- Core
			|- SystemAethera
			|- SystemAlphaCentauri
			|- SystemLuhman16
			|- KSS2_License.md
			|- KSS2Settings.cfg


### 2. Required Dependencies *(Must Be Installed)*

For KSS2 to work properly, install:

* **[Kopernicus](https://github.com/kopernicus/kopernicus/releases)** (v217+) – Core planet modding framework
* **[Kopernicus Expansion-er](https://github.com/VabienArt/KopernicusExpansion-Continueder/releases)** – Adds wormholes and special effects *(strongly recommended)*
* **[KSP Community Fixes](https://github.com/KSPModdingLibs/KSPCommunityFixes/releases)** – Boosts stability and fixes game bugs
* **[NiakoUtils](https://github.com/pkmniako/Kopernicus_VertexMitchellNetravaliHeightMap/releases)** – Enables detailed surface features *(bundled with KSS2 Core)*
* **[VertexHeightOblateAdvanced](https://github.com/jamespglaze/VertexHeightOblateAdvanced/releases/tag/1.1.4)** – Oblate object shaping *(bundled with KSS2 Core)*


 
### 3. Visual Enhancements *(Optional but Recommended)*

* **[Volumetric EVE](https://www.patreon.com/c/blackrack/posts)** – Clouds, auroras, geysers *(paid mod by Blackrack)*
* **[Scatterer](https://github.com/LGhassen/Scatterer/releases)** – Atmospheric scattering and shaders
* **[Parallax 2](https://forum.kerbalspaceprogram.com/topic/209714-112x-parallax-pbr-terrain-and-surface-objects-202/)** – High-detail terrain and surface objects
* **[Singularity](https://github.com/LGhassen/Singularity)** – Visuals for black holes and wormholes
* **[INSTANTIATOR](https://github.com/TheWhiteGuardian/Unofficial_INSTANTIATOR)** – Visuals for pulsars
* **[Distant Object Enhancement](https://github.com/net-lisias-ksp/DistantObject)** – Distant planet visibility *(not needed if using Scatterer)*
* **[PlanetShine](https://forum.kerbalspaceprogram.com/index.php?/topic/173138-112x-planetshine-0266-feb-22-2022/)** – Planetary glow and ambient lighting



### 4. General Settings File:

The **KSS2Settings.cfg** file contains several options you may want to configure (located in the **KSS2** folder):
- **SpaceAnomalies**: Enabled by default with Blueshift mod. Enables exploration of space anomalies.
- **Exotics**: Enable for rare and challenging celestial phenomena.
- **Wormholes**: Toggle the wormhole network connecting KSS2 systems.
- **HabitableWorlds**: Set to **True** to enable the habitable moon Pandor.
- **Rescale**: Choose between a 2.5x or 10x scale, requires **Sigma Dimensions** mod.
- **Asteroid Belts**: Enable/disable asteroid belts around Kerbol and other systems.

---

## Compatibility:

### Supported Mods:
- [Sterling Systems](https://forum.kerbalspaceprogram.com/topic/219609-1125-sterling-systems-v0371-mar-02-2024/)
- [Contract Configurator](https://github.com/KSP-RO/ContractConfigurator) KSS2 related contracts. V2.1.3 or greater.
- [Kerbalism](https://forum.kerbalspaceprogram.com/index.php?/topic/190382-15-110-kerbalism-311/)
- [Kerbal Health](https://forum.kerbalspaceprogram.com/index.php?/topic/155313-18-kerbal-health-163-2022-12-25/)
- [Community Resource Pack](https://github.com/UmbraSpaceIndustries/CommunityResourcePack/releases)
- [Rational Resources](https://forum.kerbalspaceprogram.com/index.php?/topic/184875-rational-resources-142-dec-25-2022/)
- [Blueshift](https://github.com/Angel-125/Blueshift/releases) This is primarily a FTL mod, but it also provides Space Anomaly support. This is needed if you would like the various interesting space anomalies in KSS2 to be available. Enable Space Anomalies in the Blueshift in-game settings.
- [WildBlueTools](https://github.com/Angel-125/WildBlueTools/releases) Primarily a collection of tools for the WildBlue mods, this provides interesting functionality for the space anomalies.
- Space Dust Next Adds a wider range of harvestable resources for both stock and modded planets.

### Not Compatible:
   - Principia
   - Galaxies Unbound (GU)
   - Previous versions of KSS2
   - KSRSS (in general, it does not appear to play well with other planet packs)
   - Parallax 1
   - Parallax Continued. Should not break the game but will disable all Parallax support in KSS2
   - Komplexity (not compatible with the KSS2 contract system)
   - Mods not mentioned in this list have not been verified and might or might not work. Install at your own risk, there's no support for these.
   - Homeswitch and Galaxy mode are **NOT** currently supported.

### Known Issues:
- **Parallax 1** and **Parallax Continued**: These are not fully supported. They will disable all Parallax effects in KSS2.
- **Legacy EVE** is incompatible, but **Volumetric EVE** is supported.

---

## Gameplay and Features:
### Contracts System:
KSS2 features a custom contract system for **Career Mode** players. Once the KSC is upgraded, mid- and late-game contracts will become available, guiding players to explore more exciting aspects of KSS2.


### Visual and Performance Tips:
- Set **Texture Quality** to the highest setting to avoid graphical issues like black orbs for some planets.
- **Maneuver Tool Bug**: The KSP 1.12 maneuver planner may cause issues with scene loads or timewarp in modified systems. It's recommended to disable the tool or use the **Community Fixes** mod, which addresses these problems.
  
  ![screenshot2](https://raw.githubusercontent.com/KSPModdingLibs/KSPCommunityFixes/master/Screenshots/settings.gif)

## Support & Community:
- **Official Support Channels**:
  - [KSP Forum](https://forum.kerbalspaceprogram.com/topic/220876-111x-112x-kerbal-star-systems-2%E2%84%A2-dev)
  - [Discord Server](https://discord.gg/acUttYPXd5)
  - [YouTube Channel](https://www.youtube.com/channel/UCrEUo4-6hNuVxUPEKNv8EcA)

---

## Help Us Improve KSS2:
Enjoying the mod? You can help support further development through donations. Every contribution helps us expand and improve the KSS2 universe!

[Donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=7VBTXAZWDDQ4S)

---

[Kerbal Star Systems 2 ](https://forum.kerbalspaceprogram.com/topic/220876-111x-112x-kerbal-star-systems-2%E2%84%A2-dev)© 2025 by [StarCrusher96 ](https://forum.kerbalspaceprogram.com/profile/148335-starcrusher96/)is licensed under CC BY-NC-ND 4.0, with all textures, except as indicated, falling under an All Rights Reserved license.


