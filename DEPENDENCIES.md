# Dependencies

What each plugin needs to load (**required**) and what it uses only when it is installed (**optional**). Everything in both lists comes with the HF Patch; without the HF Patch, install the required ones by hand. Optional mods are detected at run time (`BepInEx.Bootstrap.Chainloader.PluginInfos`) and read by reflection, never linked: when one is missing, every option, achievement or line about it is hidden and the plugin works the same without it.

## Required

| Mod | GUID | Version | Needed by | Author |
|---|---|---|---|---|
| BepInEx | – | 5.4.23 (5.4.x) | all three | BepInEx team |
| HarmonyX (`0Harmony.dll`, ships with BepInEx) | – | – | all three | BepInEx team |
| KKAPI (ModdingAPI) | `marco.kkapi` | 1.30.1+ (Campus Life, H Male Wardrobe), 1.45+ (School Optimizer) | all three | ManlyMarco |
| ExtensibleSaveFormat (BepisPlugins) | `com.bepis.bepinex.extendedsave` | – | Campus Life (its save data), School Optimizer (parked students) | BepisPlugins team |
| Sideloader (BepisPlugins) | `com.bepis.bepinex.sideloader` | – | School Optimizer (the missing zipmods list) | BepisPlugins team |

The game itself: Koikatu / Koikatsu Party main game (story mode), Unity 5.6.2 / .NET 3.5.

## Optional
### H Male Wardrobe (`joojkk.hmalewardrobe`)

No optional mods.

