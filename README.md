# Peace Aah Modpack README

This file documents the current setup so you can recreate it on another PC.

## Base Versions

- Instance name: Peace Aah
- Minecraft version: 1.21.8 (from Fabric intermediary entry in Peace Aah.json)
- Mod loader: Fabric Loader 0.18.6
- Java runtime target: Java 21

## Migration Folders To Copy

Copy these folders/files to the same Minecraft instance on the new PC:

- mods/
- resourcepacks/
- shaderpacks/
- config/
- options.txt
- Peace Aah.json

## Mods (from mods folder)

Notes:

- Version values are best-effort extracted from file names.
- If there is any mismatch, treat the file name as the source of truth.
- Some mods appear in multiple versions; keep only the one you want on the new PC.

| Mod file name                                  | Version (from file name)          |
| ---------------------------------------------- | --------------------------------- |
| AmbientSounds_FABRIC_v6.2.2_mc1.21.8           | 6.2.2_mc1.21.8                    |
| appleskin-fabric-mc1.21.6-3.0.6                | 1.21.6-3.0.6                      |
| architectury-17.0.8-fabric                     | 17.0.8-fabric                     |
| Axiom-5.1.1-for-MC1.21.8                       | 5.1.1-for-MC1.21.8                |
| camerautils-fabric-1.21.8-1.1.2                | 1.21.8-1.1.2                      |
| cardinal-components-api-7.0.0-beta.1           | 7.0.0-beta.1                      |
| cave_dust-3.0.1                                | 3.0.1                             |
| Chunky-Fabric-1.4.40                           | 1.4.40                            |
| cloth-config-19.0.147-fabric                   | 19.0.147-fabric                   |
| connectedglass-1.1.14-fabric-mc1.21.6          | 1.1.14-fabric-mc1.21.6            |
| continuity-3.0.1-beta.1+1.21.6                 | 3.0.1-beta.1+1.21.6               |
| create-fly-1.21.8-6.0.8-1                      | 1.21.8-6.0.8-1                    |
| CreativeCore_FABRIC_v2.14.7_mc1.21.8           | 2.14.7_mc1.21.8                   |
| DistantHorizons-2.3.6-b-1.21.8-fabric-neoforge | 2.3.6-b-1.21.8-fabric-neoforge    |
| DistantHorizons-2.4.5-b-1.21.8-fabric-neoforge | 2.4.5-b-1.21.8-fabric-neoforge    |
| dynamiclights-v1.9-mc1.17-1.21.9-mod           | 1.9-mc1.17-1.21.9-mod             |
| e4mc_minecraft-fabric-5.4.1                    | 5.4.1                             |
| entity_model_features_1.21.6-fabric-3.0.1      | 1.21.6-fabric-3.0.1               |
| entity_model_features_1.21.6-fabric-3.0.17     | 1.21.6-fabric-3.0.17              |
| entity_texture_features_1.21.6-fabric-7.0.13   | 1.21.6-fabric-7.0.13              |
| entity_texture_features_1.21.6-fabric-7.0.2    | 1.21.6-fabric-7.0.2               |
| Essential_1-3-10-8_fabric_1-21-8               | 1.3.10.8 (from file tag 1-3-10-8) |
| fabric-api-0.136.0+1.21.8                      | 0.136.0+1.21.8                    |
| fabric-api-0.136.1+1.21.8                      | 0.136.1+1.21.8                    |
| fabric-language-kotlin-1.13.10+kotlin.2.3.20   | 1.13.10+kotlin.2.3.20             |
| fallingleaves-2.0.1+1.21.5                     | 2.0.1+1.21.5                      |
| fusion-1.2.11-fabric-mc1.21.6                  | 1.2.11-fabric-mc1.21.6            |
| fusion-1.2.12-fabric-mc1.21.6                  | 1.2.12-fabric-mc1.21.6            |
| gameclock-fabric-2.1.0                         | 2.1.0                             |
| Geophilic v3.4.4 f15-88.mod                    | 3.4.4                             |
| HMI 5.0L3 1.21.6+                              | 5.0L3                             |
| ImmediatelyFast-Fabric-1.12.5+1.21.8           | 1.12.5+1.21.8                     |
| indium-1.0.35+mc1.21                           | 1.0.35+mc1.21                     |
| iris-fabric-1.9.6+mc1.21.8                     | 1.9.6+mc1.21.8                    |
| lithostitched-fabric-1.21.6-1.4.11             | 1.21.6-1.4.11                     |
| mcw-bridges-3.1.2-mc1.21.8fabric               | 3.1.2-mc1.21.8fabric              |
| mcw-doors-1.1.5-mc1.21.8fabric                 | 1.1.5-mc1.21.8fabric              |
| mcw-furniture-3.4.1-mc1.21.8fabric             | 3.4.1-mc1.21.8fabric              |
| mcw-lights-1.1.5-mc1.21.8fabric                | 1.1.5-mc1.21.8fabric              |
| mcw-mcwfences-1.2.1-mc1.21.8fabric             | 1.2.1-mc1.21.8fabric              |
| mcw-mcwstairs-1.0.2-mc1.21.8fabric             | 1.0.2-mc1.21.8fabric              |
| mcw-mcwwindows-2.4.2-mc1.21.8fabric            | 2.4.2-mc1.21.8fabric              |
| mcw-roofs-2.3.2-mc1.21.8fabric                 | 2.3.2-mc1.21.8fabric              |
| mcw-trapdoors-1.1.5-mc1.21.8fabric             | 1.1.5-mc1.21.8fabric              |
| modmenu-15.0.0                                 | 15.0.0                            |
| movingelevators-1.4.11-fabric-mc1.21.6         | 1.4.11-fabric-mc1.21.6            |
| mru-1.0.22+edge+1.21.8+fabric                  | 1.0.22+edge+1.21.8+fabric         |
| noisium-fabric-2.7.0+mc1.21.6-8                | 2.7.0+mc1.21.6-8                  |
| OrthoCamera-0.1.9+1.21.6                       | 0.1.9+1.21.6                      |
| placeholder-api-2.7.2+1.21.8                   | 2.7.2+1.21.8                      |
| Resourcify (1.21.8-fabric)-1.8.1               | 1.8.1                             |
| RoughlyEnoughItems-20.0.811-fabric             | 20.0.811-fabric                   |
| sodium-fabric-0.7.2+mc1.21.8                   | 0.7.2+mc1.21.8                    |
| sodium-fabric-0.7.3+mc1.21.8                   | 0.7.3+mc1.21.8                    |
| sound-physics-remastered-fabric-1.21.8-1.5.1   | 1.21.8-1.5.1                      |
| sounds-2.4.16+edge+1.21.8+fabric               | 2.4.16+edge+1.21.8+fabric         |
| supermartijn642configlib-1.1.8-fabric-mc1.21   | 1.1.8-fabric-mc1.21               |
| supermartijn642corelib-1.1.18e-fabric-mc1.21.7 | 1.1.18e-fabric-mc1.21.7           |
| supermartijn642corelib-1.1.21-fabric-mc1.21.7  | 1.1.21-fabric-mc1.21.7            |
| tectonic-3.0.4-fabric-1.21.8                   | 3.0.4-fabric-1.21.8               |
| Terralith_1.21.x_v2.5.13                       | 2.5.13 (v2.5.13 tag)              |
| tl_skin_cape_fabric_1.21.6_1.21.8-1.38         | 1.21.6_1.21.8-1.38                |
| tl_skin_cape_fabric_1.21.6_1.21.8-1.381        | 1.21.6_1.21.8-1.381               |
| travelersbackpack-fabric-1.21.8-10.8.4         | 1.21.8-10.8.4                     |
| worldedit-mod-7.3.16                           | 7.3.16                            |
| xaeroworldmap-fabric-1.21.8-1.40.11            | 1.21.8-1.40.11                    |
| yet_another_config_lib_v3-3.7.1+1.21.6-fabric  | 3.7.1+1.21.6-fabric               |

## Texture Packs (resourcepacks folder)

- §6§nBlack Loading S. [1.21.x] V1.0
- 3D Ladder
- Bare Bones 1.21.9
- Default-Dark-Mode-1.21.11-2026.4.0
- dynamiclights-v1.9-mc1.17-1.21.9-datapack
- FaithfulPBR_128_1.1p
- Farm 3D - Heycronus
- FreshAnimations_v1.10.1
- TransparentGUI-1.21.X-R1.3
- vanilla-connected-glass-0.8
- vanilla-connected-glass-0-9

## Shaders (shaderpacks folder)

- ComplementaryReimagined_r5.6.1
- Solas Shader V3.1b

## Quick Restore Checklist

1. Install Minecraft 1.21.8 with Fabric Loader 0.18.6.
2. Create or copy this instance as Peace Aah.
3. Copy mods, resourcepacks, shaderpacks, and config into the new instance.
4. Launch once and confirm no missing dependencies.
5. Keep only one version when duplicates exist (for example Sodium, Fabric API, Distant Horizons, ETF/EMF, Fusion, TL skin/cape).
