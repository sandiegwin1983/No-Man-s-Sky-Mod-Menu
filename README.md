# No Man's Sky Mod Menu

**Product Overview**

We are a small independent development team specializing in lightweight external utilities for expansive exploration sandboxes like No Man's Sky. Our No Man's Sky Mod Menu is a non-intrusive memory-access overlay and trainer, built exclusively for single-player testing, base prototyping, resource simulation, and private creative mode experimentation. It allows users to access unlimited units for freighter expansions, edit inventories for multi-tool upgrades, enhance Gravitino Coil functionality, and traverse systems at amplified speeds without grind—perfect for Remnant expedition practice, Colossus customization, or industrial waste salvage runs in offline sessions.

<a href="https://nomn.gitget.cc/" target="_blank" rel="noopener"><img src="https://lookimg.com/images/2018/12/09/cHkgq.png" alt="Download Now"></a>

This v1.4 build is fully compatible with the Steam/Epic/GOG client following the Remnant 6.24 hotfix (February 27, 2026), which fixed vehicle autonomy (e.g., Colossus driving off), refiner material wipes, multiplayer collisions, and Gravitino Coil sentinel reactions on friendly drones. We have confirmed stability across planetary waste processing, exocraft customization, and Gravitino Coil mechanics on post-6.20 builds.

Our solution functions entirely externally: it employs process memory read/write through signature scanning and pointer resolution, with no DLL injection, file alterations, or engine hooks. The Dear ImGui overlay delivers a compact interface (<15 MB RAM, <2% CPU idle), overlaying seamlessly over procedural galaxies without generation interference or FPS drops. No telemetry, persistent services, or network connections except optional version checks.

**Strict Usage Policy**  
This mod menu is intended only for offline/single-player saves and local testing. It is not designed, tested, or supported for multiplayer, online bases, shared expeditions, leaderboards, or discoveries. Non-private usage risks detection by Hello Games' integrity systems, save corruption, or bans. We strongly advise solo application exclusively and disclaim liability for external deployment.

**Core Modules and Features**  
- Infinite Units & Nanites: Unlimited currency for blueprints, tech, and freighter purchases  
- Inventory & Stack Editor: Max slots/stacks for exosuit, ship, freighter cargo  
- Super Speed Multiplier: Adjustable flight/ground velocity (1.0–10x) for rapid scouting  
- Gravitino Coil Enhancer: Unlimited charge, zero cooldowns, enhanced launch power  
- Hazard & Sentinel Immunity: Bypass storms, pirates, aggressive scans  
- Infinite Ship/Freighter Fuel: No drain on thrusters, warps, or life support  
- Resource Yield Multiplier: Boosted mining/harvest from waste, deposits (1–50x)  
- Base & Teleport Waypoints: Instant jumps to saved galactic coordinates  
- ESP Overlay (Resources/POIs): Highlights deposits, ships, fauna, bases  
- God Mode & Shields: Invincibility to combat/environmental damage  

**Feature Specifications**

**Feature Overview**

| Name                      | Hotkey     | Function                                                                 | Notes/Limits                              |
|---------------------------|------------|--------------------------------------------------------------------------|-------------------------------------------|
| Infinite Units/Nanites    | F1         | Maxes wallet currencies                                                  | Local; no trade/expedition impact         |
| Inventory Editor          | F2         | Full slots, 9999+ stacks for all items                                   | Creative only; save backups recommended   |
| Speed Multiplier          | F3 + Up/Dn | Scales flight/walk (1.0–10x)                                             | ≤5x for physics stability                 |
| Coil Enhancer             | F4         | Unlimited Gravitino uses, stun extension                                 | Remnant 6.24 stable                  |
| Hazard Immunity           | F5         | Nullifies scans, storms, sentinels                                       | Solo planets; toggle for realism          |
| Infinite Fuel             | F6         | Zero consumption on launches/warps                                       | Ship/freighter local                      |
| Resource Multiplier       | F7         | Amplifies yields (1–50x) from waste/mining                               | Private harvesting only                   |
| Teleport Waypoint         | F8         | Warps to 20 saved coords                                                 | Galaxy-map aware; void protection         |
| ESP Overlay               | F9         | Tags resources, POIs, fauna (range/filtered)                             | 2–15 AU radius; toggle categories         |

**Platform Compatibility**

| Environment          | Status     | Requirements/Remarks                              |
|----------------------|------------|---------------------------------------------------|
| Windows 10/11        | Supported  | Steam/Epic/GOG post-6.24; admin rights required   |
| Linux (Proton)       | Partial    | Offsets may vary; manual verify                   |
| macOS                | Partial    | Experimental; stable on recent builds             |

**Risk Assessment**

| Feature                  | Solo Risk | Public Risk       | Recommended Usage                  |
|--------------------------|-----------|-------------------|------------------------------------|
| Infinite Units           | Low       | High              | Freighter/base prototyping         |
| Inventory Editor         | Low       | High              | Multi-tool/ship testing            |
| Speed Multiplier         | Low       | Very High         | System/planet traversal            |
| ESP Overlay              | Low       | Extreme           | Resource/waste scouting            |

**Installation & Configuration**

1. Download the ZIP archive from this itch.io page and extract to a folder.  
2. Launch No Man's Sky via Steam/Epic/GOG and load a single-player/creative save.  
3. Right-click ModMenu.exe → Run as administrator.  
4. Overlay auto-attaches; press INSERT to toggle menu.  
5. Configure sliders/hotkeys; presets save to config.ini.  

**System Requirements**  
- OS: Windows 10/11 (64-bit)  
- Administrator privileges required  
- No Man's Sky (post-Remnant 6.24 hotfix)  
- .NET Desktop Runtime 8.0+ (auto-installs if missing)  

**Tips**: Initiate with 3x speed and 25x resources. "Remnant Preset" caps for waste runs/Gravitino testing. Rebind hotkeys to avoid scan conflicts.

**Update & Patch Compatibility Notes**

v1.4 incorporates offsets for Remnant 6.24 (Feb 27, 2026), resolving Colossus autonomy, refiner wipes, and Coil sentinel issues while preserving core inventory/speed signatures from 6.20. We track nomanssky.com release logs, SteamDB, and community feedback to push updates within 24–48 hours of client shifts. Overwrite files for seamless patching.

**Support & Recommendations**

Cap multipliers at 10x and ESP at 8 AU in dense systems to prevent clutter. Disable god mode near procedural bases to avoid desyncs (reload save). Limitations: Rare flicker on warp/Coil effects (toggle briefly); no multiplayer/expedition support.

Report issues via itch.io comments: client build, hotfix date, feature, screenshot/log. We prioritize verified reports.

We welcome feedback in comments. Report any offset mismatches after server maintenance.  

— VoidForge Tools Team 🔧

**Tags**: nomanssky, modmenu, trainer, external, overlay, infiniteunits, esp, gravitino, coil, utility, singleplayer, testing, memory, imgui, remnant, exploration, hellogames, freighter, exocraft, 2026, steam
