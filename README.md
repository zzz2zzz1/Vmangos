[![Eluna-VMaNGOS CI build](https://github.com/Niam5/Eluna-VMaNGOS/actions/workflows/vmangos.yml/badge.svg)](https://github.com/Niam5/Eluna-VMaNGOS/actions/workflows/vmangos.yml)

# VMangos-eluna
This project is a [VMangos](https://github.com/vmangos/core) version with [Eluna](https://github.com/ElunaLuaEngine/Eluna) code merged.

# Progressive Vanilla
This project is an independent continuation of the Elysium / LightsHope codebases, focused on delivering the most complete and accurate content progression system possible, including support for the patch appropriate game clients.

### Currently supported builds
- 1.12.1.5875+
- 1.11.2.5464
- 1.10.2.5302
- 1.9.4.5086
- 1.8.4.4878
- 1.7.1.4695
- 1.6.1.4544
<!--- 1.5.1.4449
- 1.4.2.4375
- 1.3.1.4297
- 1.2.4.4222-->
The original version is from [Vale](https://github.com/ValeTheVioletMote/core) and [CoolZoom](https://github.com/coolzoom),thanks for them!

### Project guidelines
- Accuracy: The point of an emulator is to recreate the functionality of that which it is emulating as closely as possible. Therefore any custom behaviour should be behind a config option and off by default.
- DB Scripting: Content should be separate from the core itself, so hardcoding scripts should be avoided where possible. When database scripting functionality is insufficient, we simply expand it.
- Full progression: The ultimate goal of this project is to have complete progression starting from patch 1.2 through 1.12. This means every piece of data must be marked with the patch in which it was added or changed to it's current state.
- Tools are great: Content creation should not require programming knowledge. We hope to eventually provide tools that allow for user-friendly editing of database scripts and content, with all data presented in human-readable form.

### Downloads
- [![vmangos CI build](https://github.com/Niam5/Eluna-VMaNGOS/actions/workflows/dev-release.yml/badge.svg)](https://github.com/Niam5/Eluna-VMaNGOS/releases/tag/latest)  Latest development binary
- [![vmangos Development DB Dump](https://github.com/vmangos/core/actions/workflows/db_dump.yml/badge.svg)](https://github.com/vmangos/core/releases/tag/db_latest)  mysql5.6 full dump, no update needed.

### Useful Links
- [Wiki](https://github.com/vmangos/wiki)
- [Discord](https://discord.gg/x9a2jt7)
- [Script Editor](https://github.com/brotalnia/scripteditor)
- [Script Converter](https://github.com/vmangos/ScriptConverter)
- Build: Same with VMangos,use cmake to generate project file,and build with vs2017.
- Run: Put lua file to lua_scripts folder in your vmangos server folder,and modify the "Eluna.ScriptPath" line in the mangosd.conf file point to "lua_scripts" folder.
