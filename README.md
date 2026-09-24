# awesome-dcs-world

> A curated list of tools, resources, guides, and communities for DCS World.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Badges: `[inactive]` = no commit/update for 12+ months · `[paid]` · `[WIP]`

## Contents

- [Getting Started](#getting-started)
  - [Free Modules](#free-modules)
- [Official Resources](#official-resources)
- [Guides & Manuals](#guides--manuals)
- [Scripting & Development](#scripting--development)
  - [Frameworks](#frameworks)
  - [Mission Utilities](#mission-utilities)
  - [Dynamic Campaigns](#dynamic-campaigns)
  - [Developer Tools](#developer-tools)
- [Mission Design](#mission-design)
  - [Mission Generators](#mission-generators)
  - [Planning Tools](#planning-tools)
  - [Training Missions](#training-missions)
  - [Third-Party Campaigns](#third-party-campaigns)
- [Flight Analysis & Debriefing](#flight-analysis--debriefing)
- [Multiplayer](#multiplayer)
  - [Communication](#communication)
  - [Server Management](#server-management)
  - [Tactical Awareness](#tactical-awareness)
  - [AI / ATC / IADS](#ai--atc--iads)
- [Notable Servers & Events](#notable-servers--events)
- [Hardware & Cockpit Integration](#hardware--cockpit-integration)
  - [Cockpit Builders](#cockpit-builders)
  - [Kneeboard & Overlays](#kneeboard--overlays)
  - [VR](#vr)
  - [Peripherals](#peripherals)
- [Customization](#customization)
  - [Mod Management](#mod-management)
  - [Skins & Liveries](#skins--liveries)
  - [Graphics Mods](#graphics-mods)
- [Aircraft & Content Mods](#aircraft--content-mods)
  - [Aircraft Mods](#aircraft-mods)
  - [Asset & Unit Packs](#asset--unit-packs)
  - [Weapon Mods](#weapon-mods)
  - [Sound Mods](#sound-mods)
- [Module-Specific Resources](#module-specific-resources)
- [Communities & Events](#communities--events)
  - [Communities](#communities)
  - [Content Creators](#content-creators)
  - [News & Media](#news--media)
- [Contributing](#contributing)

---

## Getting Started

- [DCS Beginners Guide](https://files.digitalcombatsimulator.com/en/files/3326416/) — Illustrated all-in-one primer for new players: modules, maps, controls, multiplayer and mods
- [DCS World — Official Site](https://www.digitalcombatsimulator.com/en/) — Start here: downloads, news, module store, and user files
- [DCS World Steam Edition](https://store.steampowered.com/app/223750/DCS_World_Steam_Edition/) — Free on Steam; Caucasus map and two aircraft included
- [ED Forums](https://forum.dcs.world/) — Official forum; module bug reports, changelogs, and technical discussions
- [Eagle Dynamics Discord](https://discord.gg/eagledynamics) — Official ED Discord for announcements and community chat
- [Hoggit Discord](https://discord.gg/hoggit) — ~35k members; module help channels and weekly open multiplayer sessions
- [Hoggit DCS World Wiki](https://wiki.hoggitworld.com/view/Hoggit_DCS_World_Wiki) — The community wiki: aircraft systems, scripting, peripherals, multiplayer setup

### Free Modules

DCS World ships with two permanently free aircraft and two free terrains, Caucasus and Marianas. Most paid modules also offer a 14-day free trial via the Module Manager.

- [A-29B Super Tucano (Community)](https://github.com/luizrenault/a-29b-community) — Free standalone community module with EFM, clickable cockpit, HUD/CMFD, FLIR and CCIP/CCRP (★237)
- [A-4E-C Skyhawk](https://github.com/Community-A-4E/community-a4e-c) — Community-built carrier-capable Skyhawk: clickable cockpit, custom flight model, air-to-ground radar; open source
- [DCS: Marianas Map](https://www.digitalcombatsimulator.com/en/shop/terrains/marianas_terrain/) — Free modern terrain alongside the base-game Caucasus: Guam, Rota, Tinian, Saipan and Andersen AFB; also free on Steam
- [Su-25T Frogfoot](https://www.digitalcombatsimulator.com/en/downloads/world/) — Free ground-attack aircraft included with the base game; good first module for learning weapons employment
- [TF-51D Mustang](https://www.digitalcombatsimulator.com/en/downloads/world/) — Free unarmed trainer based on the P-51D; recommended for learning basic flight and aerobatics
- [VNAO T-45C Goshawk](https://forum.dcs.world/topic/203816-vnao-t-45-goshawk/) — Free community naval jet trainer with clickable cockpit and carrier ops support; made by Virtual Naval Air Operations
- [Free Trial System](https://www.digitalcombatsimulator.com/en/shop/modules/) — Most paid modules can be trialed for 14 days via the in-game Module Manager; no purchase required

> Note: community aircraft mods (A-4E-C, T-45C, A-29B) may not be available on multiplayer servers running strict integrity check.

---

## Official Resources

- [DCS World Changelog](https://www.digitalcombatsimulator.com/en/news/changelog/) — Official per-version patch notes for every DCS World release
- [DCS World — Documentation](https://www.digitalcombatsimulator.com/en/downloads/documentation/) — Free PDF manuals for every module
- [DCS World — E-Shop](https://www.digitalcombatsimulator.com/en/shop/) `[paid]` — Modules, terrains, campaigns, and bundles from ED
- [DCS World — Texture Templates](https://www.digitalcombatsimulator.com/en/downloads/texture_templates/) — Official PSD/TGA paint kits for most aircraft
- [DCS World — User Files](https://files.digitalcombatsimulator.com/en/files/) — Community missions, liveries, mods, kneeboards, campaigns
- [Eagle Dynamics YouTube](https://www.youtube.com/@EagleDynamicsTV) — Trailers, dev updates, and tutorials from ED

---

## Guides & Manuals

- [8492nd — DCS Performance and Settings Guide](https://www.8492sqdn.net/guides/dcs/performance/) — Bottleneck diagnosis, hardware picks, Windows and GPU tweaks, per-setting impact, crash fixes
- [Chuck's Guides](https://chucksguides.com/) — Illustrated guides for almost every module: startup, systems, weapons, navigation
- [DCS on Linux](https://github.com/ChaosRifle/DCS-on-Linux) — Maintained guide, tools and workarounds for running the DCS client on Linux via Proton or Wine (★62)
- [DCShelin](https://forums.mudspike.com/t/introducing-the-michelin-guide-for-dcs-world/7902) `[inactive]` — One pilot's Michelin-style star ratings for modules, terrains, and campaigns; PDF last revised March 2022
- [ED Forums — Guides & Tutorials](https://forum.dcs.world/forum/42-guides-amp-tutorials/) — Community tutorials section on the official forum
- [Heatblur F-14 Manual](https://f14.manuals.heatblur.se/) — The F-14A/B online manual; covers pilot seat, RIO station, and Jester AI
- [Heatblur F-4E Manual](https://f4.manuals.heatblur.se/) — Heatblur's online F-4E manual: pilot and WSO cockpits, systems, weapons, Jester AI and its Lua modding API
- [Hoggit Wiki — Guides](https://wiki.hoggitworld.com/view/Hoggit_DCS_World_Wiki) — BFM, carrier ops, peripherals, scripting
- [Hoggit Wiki — Terrain Information](https://wiki.hoggitworld.com/view/Category:Terrain_Information) — Per-terrain reference for 11 DCS maps up to Cold War Germany: airbase names and IDs, map size, notable features
- [TAW Radar Simulator](https://tawdcs.org/radar-f15/) — Browser-based F-15 radar trainer; good starting point before going BVR online

---

## Scripting & Development

### Frameworks

- [dcs-sms](https://github.com/nielsvaes/dcs-sms) — Lightweight scripting framework, Mission Editor prefab manager and host-side CLI in one project (★42)
- [MIST — Mission Scripting Tools](https://github.com/mrSkortch/MissionScriptingTools) — Lightweight Lua utility library; still the standard dependency for CTLD, CSAR, and many community scripts (★220)
- [MIST Documentation — Hoggit Wiki](https://wiki.hoggitworld.com/view/Mission_Scripting_Tools_Documentation) — MIST API reference
- [MOOSE](https://github.com/FlightControl-Master/MOOSE) — Massive OOP Lua framework: AI dispatchers, ATIS, MANTIS IADS, CTLD, CSAR, AirBoss… (★350)
- [MOOSE Documentation](https://flightcontrol-master.github.io/MOOSE/) — Official docs hub: beginner tutorials, advanced guides, and links to the auto-generated class reference
- [pydcs](https://github.com/pydcs/dcs) — Generate and edit `.miz` files from Python; powers DCS Liberation and Retribution (★189)
- [VEAF Mission Creation Tools](https://github.com/VEAF/VEAF-Mission-Creation-Tools) — Lua + Python for git-versioned DCS missions with dynamic spawning, ATIS, and radio menus (★25)
- [VEAF Documentation](https://veaf.github.io/documentation/) — VEAF scripting reference

### Mission Utilities

- [AAA Flak Barrage Script](https://forum.dcs.world/topic/383842-aaa-flak-barrage-effect-script-v4/) — Place flak zones in the Mission Editor for heavy AAA barrages without spawning masses of AI guns; by bandit648
- [AIEN — AI Enhancement Script](https://github.com/Chromium18/AIEN) — Ground AI script: suppression, reactions under fire, infantry dismounts, automatic artillery fire missions
- [CSAR — Combat Search and Rescue](https://github.com/ciribob/DCS-CSAR) `[inactive]` — Rescues ejected pilots and delivers them to a friendly FARP; requires MIST
- [CTLD — Complete Troops & Logistics Deployment](https://github.com/ciribob/DCS-CTLD) — Helicopter troop transport, sling-load logistics, FARP construction, JTAC
- [DATIS — DCS ATIS via SRS](https://github.com/rkusa/DATIS) `[inactive]` — Generates spoken ATIS over SRS using in-mission weather; supports AWS Polly and Google TTS (★110)
- [DCS-Hound](https://github.com/uriba107/DCS-Hound) — Realistic ELINT script: triangulates emitting radars from multiple platforms, draws F10 uncertainty ellipses (★43)
- [DCS-SimpleTextToSpeech](https://github.com/ciribob/DCS-SimpleTextToSpeech) `[inactive]` — Lua script adding text-to-speech and MP3 playback over SRS; a dependency of many missions (★23)
- [HoundTTS](https://github.com/uriba107/HoundTTS) — Native C++ TTS extension sending Piper, SAPI, Azure, Google or ElevenLabs speech to SRS from mission scripts
- [Splash Damage Script](https://github.com/stephenpostlethwaite/DCSSplashDamageScript) — TNT-equivalent blast modelling, napalm, WP, and secondary effects for DCS explosions

### Dynamic Campaigns

- [DCC — Digital Crew Chief](https://github.com/kilcekru/dcc) — Zero-config dynamic campaign app: auto-generated CAP/CAS/strike sorties, persistence, multiplayer (★101)
- [DCE — Dynamic Campaign Engine](https://github.com/bbirchnz/dce-campaign-builder) — Community builder for the original MBot/Minsky persistent turn-by-turn campaign engine
- [DCT — Dynamic Campaign Tools](https://github.com/jtoppins/dct) `[inactive]` — Lua framework for persistent server-side campaigns; scenarios built from templates, no external program needed
- [DCT Documentation](https://jtoppins.github.io/dct/) — Full docs and quick-start for DCT
- [DCS Liberation](https://github.com/dcs-liberation/dcs_liberation) — Turn-based SP/co-op dynamic campaign generator: persistent front-line, IADS, JTAC, SEAD (★799)
- [DSMC](https://dsmcfordcs.wordpress.com/) — Scenery persistence mod: saves unit damage, positions and warehouse stocks into a new .miz mission
- [Foothold by Leka](https://files.digitalcombatsimulator.com/en/files/3341245/) — Maintained Foothold zone-capture missions: Cold War, Modern and Vietnam eras, persistence, multi-language
- [Foothold — zoneCommander](https://github.com/Dzsek/zoneCommander) `[inactive]` — Zone-capture PvE sandbox engine behind the Foothold missions; persistent progress and AI logistics (★26)
- [Pretense](https://github.com/GoldJohnKing/pretense) `[inactive]` — In-mission sandbox: mercenary economy, AI logistics, XP progression, persistence
- [Retribution](https://github.com/dcs-retribution/dcs-retribution) — Active Liberation fork; adds Splash Damage, CTLD, improved front-line mechanics (★177)

### Developer Tools

- [acEFM](https://github.com/Zaretto/acEFM) — Bridge DLL running a JSBSim flight model as a DCS EFM, configured from XML; for aircraft mod developers (★18)
- [Blender EDM Exporter](https://github.com/EagleDynamics/Blender-EDM-Exporter) — Official ED Blender plugin exporting 3D models to EDM: animation args, connectors, collisions, damage (★56)
- [DCS Lua Datamine](https://github.com/Quaggles/dcs-lua-datamine) — Auto-dumped Lua tables for every weapon, unit and sensor; the reference for RCS, IR and missile data (★134)
- [DCS Mission Translator](https://github.com/leonchen83/miz-translator) — AI-translates .miz mission and campaign text into Chinese, Japanese, Korean and 19 more languages (★24)
- [DCS Modding Documentation](https://modding.caffeinesimulations.com/) — DCS OpenSource reference for aircraft mods: Lua device stubs, EFM API, indicators, draw args
- [DCS Unit Tester](https://github.com/Quaggles/dcs-unit-tester) — Replays recorded tracks after each DCS patch and checks a Lua assertion per track to catch module regressions
- [DCS-Basic-EFM-Template](https://github.com/IGServal/DCS-Basic-EFM-Template) `[inactive]` — Enhanced External Flight Model template for DCS module developers (★34)
- [DCS-BIOS](https://github.com/DCS-Skunkworks/dcs-bios) — Exports cockpit state over serial/UDP; the base layer for physical panel integration (★433)
- [DCS-BIOS Arduino Library](https://github.com/DCS-Skunkworks/dcs-bios-arduino-library) — Arduino/ESP32 client library for DCS-BIOS (★73)
- [DCS-fiddle](https://github.com/flying-dice/dcs-fiddle) — Browser-based DCS Lua REPL; test scripts without restarting the mission
- [DCS-gRPC Go bindings](https://github.com/DCS-gRPC/go-bindings) `[inactive]` — Go protobuf/gRPC bindings for the DCS-gRPC API
- [DCS-gRPC rust-server](https://github.com/DCS-gRPC/rust-server) — Rust gRPC server embedded in DCS; exposes mission events and commands to external clients (★118)
- [DCS Lua Debugger](https://github.com/Reousa/VSCode-DCS-Debugger) `[inactive]` — VSCode debug adapter for Lua running inside DCS missions
- [DCS Lua Definitions](https://github.com/omltcat/dcs-lua-definitions) — VS Code IntelliSense and type hints for DCS World Lua scripting
- [DCS Scratchpad](https://github.com/rkusa/dcs-scratchpad) — In-game scratchpad overlay for notes and coordinates (★202)
- [Hoggit DCS SSE Wiki](https://wiki.hoggitworld.com/view/Simulator_Scripting_Engine_Documentation) — Reference for the in-game Lua scripting environment: functions, classes, callbacks
- [Quaggles DCS Input Command Injector](https://github.com/Quaggles/dcs-input-command-injector) — Adds custom per-aircraft keybinds that survive updates without editing default input Lua
- [Skynet-IADS](https://github.com/walder/Skynet-IADS) `[inactive]` — EWR stations datalink SAM sites; SAMs go cold on HARM detection (★226)
- [skyeye](https://github.com/dharmab/skyeye) — Self-hosted AI GCI bot with voice recognition and neural TTS; runs over SRS and DCS-gRPC (★121)
- [Tacview ACMI SDK](https://raia-software-inc.gitbook.io/tacview/technical-documentation/acmi-telemetry-file-format) — ACMI format spec and SDK for building Tacview-compatible exporters
- [Twitch2DCS](https://github.com/rthom91/twitch2dcs) — Shows Twitch chat inside DCS so VR streamers can read it without removing the headset
- [undo](https://github.com/snwfke/undo) `[WIP]` — Mission Editor extension adding undo to DCS; installed by an executable, no manual file patching

---

## Mission Design

### Mission Generators

- [BriefingRoom for DCS](https://github.com/DCS-BR-Tools/briefing-room-for-dcs) — GUI/CLI generator producing SP/MP `.miz` files in seconds; custom templates, scripted SAMs and JTAC (★306)
- [CombatFlite](https://www.combatflite.com/) — Free mission planner with DCS export, briefing packs, kneeboard cards, and airspace deconfliction
- [DCS Real Weather](https://github.com/evogelsa/dcs-real-weather) — Fetches a live METAR and patches the weather block in a `.miz` before server restart (★36)
- [DCS WeatherInjector](https://github.com/destotelhorus/DCS-WeatherInjector) `[inactive]` — CLI/scheduled METAR and datetime injection for dedicated servers
- [DCS Web Editor](https://dcs-web-editor.vercel.app/) — Browser mission editor: multi drag-select, copy/paste, undo/redo, and porting missions between theaters
- [RotorOps](https://github.com/spencershepard/RotorOps) `[inactive]` — Helicopter mission generator and scripts: dynamic ground war, staged zone capture, SP/co-op/MP (★92)
- [VEAF Mission Converter](https://github.com/VEAF/VEAF-mission-converter) `[inactive]` — Unpacks a `.miz` into a versionable folder, edit, then rebuild with VEAF scripts injected

### Planning Tools

- [Combined Ops](https://www.combinedops.org/) — Multi-squadron ops platform: mission planner, ATO/ACO generation from .miz files, airspace control
- [DCS Planner](https://dcsplanner.com/) — Web app to plan mission steerpoints, geolines, and map drawings
- [DCS Web Planner](https://dcs-web-editor.github.io/dcs-web-viewer-deploy/) — Browser mission planner, no install; includes kneeboard generator and DTC export/import
- [DTC for DCS](https://github.com/the-paid-actor/dcs-dtc) — Data Transfer Cartridge app for F-16, F/A-18, F-15E, AH-64D and A-10C II; CombatFlite import (★227)
- [JAFDTC](https://github.com/51st-Vfw/JAFDTC) — Data cartridge tool for A-10C, F-15E, F-16C and F/A-18C; loads avionics via the clickable cockpit
- [MizMap](https://github.com/mizmap/mizmap) — Live browser map for mission creators; place and track units in real time while building

### Training Missions

- [Bandit on Demand](https://files.digitalcombatsimulator.com/en/files/3320850/) `[inactive]` — BFM/BVR SP/MP mission; spawn any AI aircraft type via voice command or F10 menu
- [BFM Gun-only Practice v2.1](https://files.digitalcombatsimulator.com/en/files/3325527/) `[inactive]` — 1v1 cannon-only BFM on Caucasus and Marianas
- [Caucasus Training Map by NZArmA](https://forum.dcs.world/topic/242333-nzarma-training-space/) `[inactive]` — AAR, interception, escort, mobile targets, JTAC, SAM — all in one mission
- [DCS OVERLOAD Caucasus](https://github.com/srogers909/DCS_OVERLOAD_Caucasus) `[inactive]` — Air-to-air training with respawning aggressors, situational awareness focus
- [Gunthrek Academy F/A-18C (Bagel Fixpack)](https://files.digitalcombatsimulator.com/en/files/3344992/) — Free four-block Hornet school: nav, air-to-ground, air-to-air, carrier ops; 100+ community fixes
- [Hoggit Training Map](https://wiki.hoggitworld.com/view/Hoggit_Training_Map) — 24/7 community training server on Caucasus with airfields, SAM threats, and range targets
- [The Universal Mission](https://github.com/akaAgar/the-universal-mission-for-dcs-world) — Dynamic SP/PvE mission: procedural tasking, 325+ voiced radio calls, career mode, 6 theaters (★85)
- [Through the Inferno](https://www.throughtheinferno.com/) — Dynamic action and training missions with randomized spawns, objectives, and JTAC, for SP and co-op on many maps

### Third-Party Campaigns

- [Baltic Dragon Campaigns](https://www.digitalcombatsimulator.com/en/shop/campaigns/?arrFilter_727_304101684=Y&set_filter=Y) `[paid]` — Raven One, The Gamblers, The Rampagers, Arctic Thunder; extensive voice work
- [Bunyap Campaigns](https://www.digitalcombatsimulator.com/en/shop/campaigns/?arrFilter_727_1777768568=Y&set_filter=Y) `[paid]` — F-16C Red Flag 21-1 and MiG-21bis Constant Peg; heavily researched Nevada training-range scenarios
- [Free Community Campaigns](https://files.digitalcombatsimulator.com/en/files/filter/type-is-campaign/localization-is-english/apply/) — Hundreds of free player-made campaigns on ED User Files
- [F-14 Speed & Angels](https://www.digitalcombatsimulator.com/en/shop/campaigns/f-14_speed_and_angels_campaign/) `[paid]` — Reflected Simulations Tomcat campaign with ex-F-14 pilot Paco Chierici: RAG training, then combat over the Marianas
- [Reflected Simulations](https://www.digitalcombatsimulator.com/en/shop/campaigns/?arrFilter_727_1324072227=Y&set_filter=Y) `[paid]` — WWII through modern campaigns (P-47, P-51, Spitfire, F-14, F-4E); known for writing and voice work
- [Sedlo's Free Campaigns](https://files.digitalcombatsimulator.com/en/files/filter/user-is-Sedlo/apply/) — 25 free single-player and co-op campaigns and missions, incl. Bold Cheetah and Gulf Guardian

---

## Flight Analysis & Debriefing

- [Logbook](http://logbook.ansirial.it) — Automatically records single- and multiplayer flight history and career progress
- [ReplayDeck](https://github.com/SYNTAX-DCS/ReplayDeck) — Rewind a DCS track replay: timeline of every launch, hit, kill and ejection, named marks, slow motion
- [SRS Recorder](https://github.com/wrycu/srs_recorder) `[inactive]` — Records SRS radio transmissions timestamped alongside Tacview playback; requires DCS-gRPC
- [Tacview](https://www.tacview.net/) — 3D flight debrief tool recording to `.acmi`; free Starter edition, paid tiers add telemetry charts and online debriefs
- [Tacview — DCS Integration Guide](https://www.tacview.net/documentation/dcs/) — How to enable the built-in Tacview recorder in DCS
- [Tacview 2.0 Preview](https://www.tacview.net/product/tacview2/en/) `[WIP]` — Next-gen rewrite: multi-viewport, real terrain, addon scripting

---

## Multiplayer

### Communication

- [DCSServerBot](https://github.com/Special-K-s-Flightsim-Bots/DCSServerBot) — Python/Discord bot for server admin: stats, slot blocking, SRS/LotATC/Tacview/Olympus integrations, 30+ plugins (★123)
- [SRS — SimpleRadioStandalone](https://github.com/ciribob/DCS-SimpleRadioStandalone) — Open-source VoIP radio tied to cockpit frequencies; present on almost every multiplayer server (★558)
- [UniversRadio](https://tacnoworld.fr/) `[inactive]` `[paid]` — TeamSpeak-based radio sim; models range, terrain masking, modulation, and encryption

### Server Management

- [Aterfax/DCS-World-Dedicated-Server-Docker](https://github.com/Aterfax/DCS-World-Dedicated-Server-Docker) — Docker image for DCS World Server on Linux via Wine; companion images for Retribution, Olympus, DCSServerBot (★73)
- [dcs-server-wine](https://github.com/ActiumDev/dcs-server-wine) — Automated headless DCS + SRS install and management scripts for Linux; multi-instance support
- [DCS World Dedicated Server (ED)](https://www.digitalcombatsimulator.com/en/downloads/world/server/) — ED's official headless dedicated server: modular installer, setup notes, web GUI control, default ports
- [DCSServerBot](https://github.com/Special-K-s-Flightsim-Bots/DCSServerBot) — See Communication; also handles server admin, slot blocking, weather injection, extension management
- [DCSOlympus](https://github.com/Pax1601/DCSOlympus) — Real-time RTS map control: spawn, task, and remove units on a live server via web map; Blue/Red GM modes (★355)
- [FunkMan](https://github.com/funkyfranky/FunkMan) `[inactive]` — Discord bot interface for MOOSE-based DCS multiplayer servers (★19)
- [Perun](https://github.com/szporwolik/perun) `[inactive]` — Lua plugin exporting sim data to MySQL; merges SRS and LotATC for unified analytics dashboards

### Tactical Awareness

- [DCSOlympus](https://github.com/Pax1601/DCSOlympus) — Live map showing all coalition units; coalition view can be restricted for realistic ops
- [Hoggit Wiki — Getting Started with GCI/AWACS](https://wiki.hoggitworld.com/view/Getting_started_with_GCI/AWACS) — Controlling as GCI/AWACS: BRAA and bullseye calls, brevity, checklists, SRS and LotATC workflow
- [Hoggit Wiki — JTAC](https://wiki.hoggitworld.com/view/JTAC) — Human JTAC primer: check-in, 9-line, talk-ons, control types, keyhole CAS, lasing via Combined Arms or CTLD, FAC(A)
- [LotATC](https://www.lotatc.com/) `[paid]` — GCI/ATC radar client+server with realistic radar coverage, IFF, and BRAA tools; integrates with SRS
- [LotATC — Hoggit Wiki](https://wiki.hoggitworld.com/view/LotATC) — How to connect to a LotATC server and perform GCI
- [peace-eye](https://github.com/pbzweihander/peace-eye) `[inactive]` — Desktop AWACS/GCI simulator using Tacview and DCS World data (★22)
- [skyeye](https://github.com/dharmab/skyeye) — Self-hosted AI GCI bot; handles PICTURE, BOGEY DOPE, DECLARE, SPIKED calls over SRS (★121)
- [Sneaker — WebGCI](https://github.com/Aterfax/sneaker) — Web-based GCI situational awareness dashboard pulling from DCS-gRPC
- [StandaloneRadarControl](https://github.com/Wizxrd/StandaloneRadarControl) — Standalone radar scope and control app for DCS World GCI (★43)

### AI / ATC / IADS

- [Aerosimics A.R.E.S.](https://www.aerosimics.com/) `[paid]` — Voice-controlled ATC and air battle management on any map: ground, tower, approach, AWACS, GCI, JTAC
- [AI_ATC Nellis AFB](https://github.com/Avalanche110/AI_ATC_Nellis_AFB) — Script adding AI-controlled ATC and ground traffic to Nellis AFB
- [DATIS](https://github.com/rkusa/DATIS) `[inactive]` — Generates airfield and carrier ATIS broadcasts over SRS from in-mission weather (★110)
- [DCS AI REVAMP](https://forum.dcs.world/topic/383084-dcs-ai-revamp-a-dynamic-battlefield-and-advanced-ground-ai-system) `[WIP]` — Scripted dynamic battlefield with smarter, more reactive ground AI
- [DCS Airspace by Combined Ops](https://airspace.combinedops.org) — Free web GCI/AWACS/ATC radar client fed by DCS Olympus: IFF, BRAA, auto PICTURE, intercept cut-offs, ACO overlay, SRS
- [Medusa IADS](https://github.com/medusa-iads/medusa) — Modern IADS script: customizable doctrines, Pk-based engagement, kinematic HARM detection, no dependencies
- [MOOSE AirBoss](https://flightcontrol-master.github.io/MOOSE_DOCS/Documentation/Ops.Airboss.html) — Scripted LSO grading, recovery tanker management, and carrier ATC
- [MOOSE MANTIS](https://flightcontrol-master.github.io/MOOSE_DOCS/Documentation/Functional.Mantis.html) — EWR-controlled SAM management; compatible with Skynet-IADS behavior
- [Skynet-IADS](https://github.com/walder/Skynet-IADS) `[inactive]` — The reference IADS script: EWR datalinks SAM sites, SAMs go cold on HARM detection, supports HighDigitSAMs (★226)
- [skyeye](https://github.com/dharmab/skyeye) — Modern OverlordBot replacement; better speech recognition and correct brevity procedures (★121)

---

## Notable Servers & Events

### Persistent Servers

- [104th Phoenix](https://104thphoenix.com/) — International virtual squadron founded in 2006; runs donation-funded public PvP servers with integrity-check rules
- [4YA Servers](https://discord.com/invite/4ya) — Multi-map PvE/PvP (Caucasus, WWII Normandy, others); 24/7
- [Blue Flag](https://wiki.buddyspike.net/) — PvP dynamic campaign across multiple eras (Cold War, 80s, Modern); run by BuddySpike
- [Contention — Strike Package Studios](https://live.strikepackagestudios.com/home) — Persistent dynamic PvP campaign servers with live web maps; modern and Cold War rulesets
- [Heatblur Cold War Server](https://discord.com/invite/heatblur-simulations) — Ex-Enigma's Cold War PvP/PvE, run by Heatblur since 2024; Caucasus hex-territory campaign; [Enigma V1 source](https://github.com/Enigma1989YT/Enigma-Cold-War-V1-Public)
- [Growling Sidewinder Server](https://discord.gg/ubeHQw9QEF) — High-population fast jet PvP; stats at stats.growlingsidewinder.com
- [Hoggit GAW — Georgia At War](https://atwar.online/gaw.php) — Hoggit's flagship Caucasus persistent server; new-pilot friendly
- [Hoggit PGAW — Persian Gulf At War](https://atwar.online/pgaw.php) — GAW's Persian Gulf counterpart
- [Rotorheads](https://forum.dcs.world/topic/239590-rotorheads-helicopter-oriented-pve/) — Helicopter-only persistent PvE server: FARP deployment, sling-load logistics, CSAR, mandatory training
- [Wings Over Normandy](https://www.wingsovernormandy.com/) — 24/7 dynamic WWII campaign over Normandy: Allied vs Axis seasons, persistent target damage, live scoreboard; run by AMVI

### Events & Competitions

- [Strike Fighter League](https://www.the-sfl.com/) — Competitive DCS air combat league: speed, precision and accuracy trials plus a dogfight bracket, broadcast live
- [Virtual Air Festivals](https://virtualairfestivals.com/) — DCS aerobatic-team airshows (formerly Virtual Airshows): international, European and summer air festivals

---

## Hardware & Cockpit Integration

### Cockpit Builders

- [AH-64D TEDAC v2.0 (MilKris666)](https://github.com/MilKris666/-DCS-AH-64D-TEDAC-v2.0-) — DIY 1:1 AH-64D TEDAC with 8-inch display and adjustable grips; 3D-printed, Leo Bodnar boards, no coding needed (★57)
- [BojoteX/CockpitOS](https://github.com/BojoteX/CockpitOS) — ESP32 firmware for DCS-BIOS panels; USB/Wi-Fi/BLE and TFT displays, no Arduino IDE needed
- [Bort](https://github.com/DCS-Skunkworks/Bort) — DCS-Skunkworks UI for browsing and live-testing DCS-BIOS control references while building panels (★56)
- [DCS-BIOS](https://github.com/DCS-Skunkworks/dcs-bios) — Exports cockpit state over serial/UDP; required by virtually every hardware integration tool (★433)
- [DCS-BIOS Arduino Library](https://github.com/DCS-Skunkworks/dcs-bios-arduino-library) — Arduino/ESP32 client library for DCS-BIOS panels (★73)
- [DCSFlightpanels](https://github.com/DCS-Skunkworks/DCSFlightpanels) `[inactive]` — Saitek/Logitech panel and Stream Deck configurator via DCS-BIOS; supports Radio Panel sim and SRS PTT
- [ED Forums — Home Cockpits](https://forum.dcs.world/forum/181-home-cockpits) — The official forum section for simpit builds
- [fsmapper](https://github.com/opiopan/fsmapper) — Builds touchscreen virtual instrument panels and remaps devices for DCS and MSFS; Lua-scripted (★42)
- [Helios](https://github.com/HeliosVirtualCockpit/Helios) — Touchscreen virtual cockpit builder with per-aircraft profiles; communicates via exports.lua (★251)
- [Hoggit Wiki — DCS-BIOS / Cockpit Building](https://wiki.hoggitworld.com/view/DCS_Bios_/_Cockpit_Building) — Getting started with cockpit building and DCS-BIOS
- [Ikarus](https://github.com/s-d-a/Ikarus) `[inactive]` — Virtual cockpit gauges on a secondary monitor or tablet via DCS ExportScript
- [OpenHornet](https://github.com/jrsteensen/OpenHornet) — Open-source 1:1 scale F/A-18C cockpit simulator with full build docs (★425)
- [SimFeedback-AC-Servo](https://github.com/SimFeedback/SimFeedback-AC-Servo) — Open-source AC servo motion simulator platform for flight sims (★328)
- [TouchDCS](https://github.com/charliefoxtwo/TouchDCS) — Bridges DCS-BIOS to TouchOSC and other OSC apps so a tablet becomes a clickable cockpit panel (★43)
- [WCtrlDcsBiosBridge](https://github.com/landre-cerp/WCtrlDcsBiosBridge) — Bridges WINCTRL (ex-WINWING) CDUs and front panels to DCS through DCS-BIOS (★36)

### Kneeboard & Overlays

- [Aerodrome Data and Frequencies](https://files.digitalcombatsimulator.com/en/files/3312200/) — Kneeboard set with frequencies, navaids, coordinates, runway headings and magvar for every DCS map
- [Capt Zeen Helios Profiles](http://www.captzeen.com/helios/profiles.asp) `[inactive]` — Large library of Helios profiles with monitor configurations for many aircraft
- [DCS Moving Map](https://movingmap.bergison.com) — Windows and Android real-time moving map covering all DCS theaters
- [DCS Live Map](https://dcs-web-editor.github.io/dcs-web-viewer-deploy/live/) — Free moving map for OpenKneeboard or the in-game browser; many options and layers
- [DCS SAM Threat Guide](https://files.digitalcombatsimulator.com/en/files/3331424/) — Kneeboard reference for SAM systems, ranges, and threat recognition
- [DCS UFC X](https://github.com/pet333r/pw-dev_script) — Android touchscreen UFC/ICP panel app for data entry into DCS aircraft
- [Community DCS-ExportScripts Library](https://github.com/asherao/DCS-ExportScripts) `[inactive]` — Community continuation of DCS-ExportScripts adding modules for the DCS Interface Stream Deck plugin (★107)
- [DCS Interface for StreamDeck](https://github.com/enertial/streamdeck-dcs-interface) — Stream Deck plugin with DCS cockpit event bindings and state-driven button images
- [DCS:The Way](https://github.com/jonsky752/DCSTheWay) — Maintained fork pushing F10-map markpoints into the aircraft as steerpoints; adds CH-47F, C-130J, Gazelle, NS430 (★16)
- [Digital Kneeboard Simulator](https://www.digitalkneeboardsimulator.com/) — Web app for flight plans, loadouts, comm cards, and kneeboard export
- [GV5Js Datacard Generator](https://forum.dcs.world/topic/261081-gv5js-datacard-generator) — Generates printable mission datacards as DCS kneeboard pages
- [Kneeboard Builder](https://dcskneeboardbuilder.com/) `[inactive]` — Converts PDFs to DCS kneeboard images; per-aircraft profile management
- [OpenKneeboard](https://github.com/OpenKneeboard/OpenKneeboard) — VR and 2D kneeboard overlay; graphics-tablet annotation, PDF nav, DCS radio log, HOTAS bindings (★358)
- [Shark Planner](https://github.com/okopanja/SharkPlanner) — Companion app that enters waypoints into the Ka-50 ABRIS/PVI-800 and other nav systems
- [Simtools.app](https://www.simtools.app) — Web app to build and download custom aircraft checklists and kneeboards
- [SlipHavoc DCS-Kneeboards](https://github.com/SlipHavoc/DCS-Kneeboards) — Pre-made kneeboard set covering most popular modules

### VR

- [DCS VR Optimization Guide](https://www.gamersbynight.com/dcs-settings-vr/) — Step-by-step for OpenXR, MT mode, and VR performance tuning in DCS 2.8+
- [HTCC — Hand Tracking Cockpit Clicking](https://github.com/fredemmott/HTCC) — Hand-tracking cockpit interaction for VR flight simulators (★74)
- [fholger/vrperfkit](https://github.com/fholger/vrperfkit) `[inactive]` — FSR/NIS/CAS upscaling and foveated rendering for SteamVR/OpenVR (★1463)
- [mbucchia/OpenXR-Toolkit](https://github.com/mbucchia/OpenXR-Toolkit) `[inactive]` — FSR/NIS upscaling and foveated rendering for OpenXR; EOL, last release Apr 2023, author advises against installing
- [mbucchia/Quad-Views-Foveated](https://github.com/mbucchia/Quad-Views-Foveated) `[inactive]` — OpenXR foveated rendering layer for Pimax Crystal, Quest Pro, and other eye-tracked headsets (★215)
- [OpenKneeboard](https://openkneeboard.com/) — See Kneeboard & Overlays; essential in-headset kneeboard overlay with tablet-pen support
- [OpenXR API Layers GUI](https://github.com/fredemmott/OpenXR-API-Layers-GUI) — View, enable, disable and reorder OpenXR API layers; flags broken or conflicting ones (★85)
- [Reshade VREM2](https://github.com/lefufu/DCS-world-reshade-VREM2) — DCS sharpening and visual enhancement Reshade addon; integrity-check safe
- [VectorXR](https://github.com/DienerTech/vectorxr) — OpenXR layer with stereo depth, head-pivot and quad-views foveated rendering, plus per-app profiles (★51)
- [VRLowdown — DCS on Meta Quest](https://vrlowdown.com/dcs-world-quest-2/) — DCS setup guide for Meta Quest (Air Link, Virtual Desktop, optimizations)

### Peripherals

- [AITrack](https://github.com/AIRLegend/aitrack) `[inactive]` — Webcam face tracker feeding OpenTrack via neural net; low CPU, no IR hardware needed
- [Chuck's Guides — HOTAS Sections](https://chucksguides.com/) — Recommended HOTAS bindings for each module
- [ControllerBuddy](https://controllerbuddy.org/) — Game controller mapping tool for flight sims; profiles for most DCS modules (★177)
- [DCS Community Keybinds](https://github.com/Munkwolf/dcs-community-keybinds) `[inactive]` — Curated keybind packs adding missing bindings for most modules; pairs with Quaggles' Injector (★110)
- [dcspy](https://github.com/emcek/dcspy) — Logitech keyboard LCD and LED device integration for DCS aircraft (★22)
- [DCS Detent Calculator](https://github.com/asherao/DCS-Detent-Calculator) `[inactive]` — Spreadsheet that finds throttle detent positions for afterburner and idle cutoff
- [DelanClip](https://delanclip.com/) `[paid]` — Affordable IR LED head-tracking clip; works with OpenTrack and TrackIR software
- [ED User Files — Device Profiles](https://files.digitalcombatsimulator.com/en/files/filter/type-is-profile/apply/) — Official repository of 700+ community HOTAS and controller profiles, filterable by aircraft
- [EyeTrackVR](https://github.com/EyeTrackVR/EyeTrackVR) — DIY open-source eye-tracking for VR headsets; ESP32 firmware + PC software
- [FOXTracker](https://github.com/xuhao1/FOXTracker) `[inactive]` — Facial head pose tracker for gaming; alternative to TrackIR and AITrack (★488)
- [Fred's Controller Tester](https://github.com/fredemmott/Freds-Controller-Tester) — DirectInput/XInput tester for sim devices: 128+ buttons, identical vJoy devices told apart, axis-range check (★37)
- [HidHide](https://github.com/nefarius/HidHide) — Windows device firewall hiding HID devices from games; stops DCS seeing duplicate or virtual controllers (★1535)
- [Hoggit Peripherals Guide](https://wiki.hoggitworld.com/view/Peripherals_Guide) — Hardware overview of head trackers, HOTAS, joysticks, throttles, collectives and rudder pedals for DCS
- [Joystick Diagrams](https://joystick-diagrams.com/) — Generates printable layout diagrams from your DCS bindings
- [Joystick Gremlin](https://github.com/WhiteMagic/JoystickGremlin) — vJoy-based HOTAS remapper: modes, response curves, macros, device merging, Python plugins (★450)
- [Joystick Gremlin EX](https://github.com/muchimi/JoystickGremlinEx) — 64-bit Joystick Gremlin fork: vJoy remapping plus OSC, MIDI, TTS and two-way Stream Deck via Bitfocus Companion (★127)
- [LookPilot](https://lookpilot.app/) `[paid]` — Webcam 6DoF head and eye tracking with TrackIR emulation; Windows and Linux, 14-day trial
- [MOZA Flight](https://mozaracing.com/collections/flight-series) `[paid]` — Force-feedback stick bases (AB6, AB9), grips, throttles and panels for flight sims
- [OpenTrack](https://github.com/opentrack/opentrack) — Free head-tracking software; supports FaceTrackNoIR, Aruco, IR clip, FreeTrack output (★5143)
- [RealSimulator](https://realsimulator.com/) `[paid]` — FSSB-R3 force-sensing stick bases and replica F-16 and F/A-18 grips; a staple of DCS Viper and Hornet pits
- [RS Mapper](https://forum.dcs.world/topic/175248-rs-mapper-release) `[inactive]` — Maps advanced HOTAS modes and shift states that DCS does not expose natively
- [SimShaker for Aviators](https://simshaker-for-aviators.github.io/) — Drives bass shakers and haptic seats from DCS telemetry: gear, stall, gun, AoA, touchdown
- [Thrustmaster](https://www.thrustmaster.com/) `[paid]` — HOTAS Warthog (A-10C replica), Viper and TCA lines; Warthog MKII base adds Hall-effect sensors and multi-grip support
- [Tobii Eye Tracker 5](https://gaming.tobii.com/games/dcs-world/) `[paid]` — Screen-mounted eye and head tracker giving 6DoF head tracking in DCS with nothing to wear
- [TrackIR](https://www.trackir.com/) `[paid]` — NaturalPoint's IR head tracker; the 6DoF reference device that DCS supports natively and most alternatives emulate
- [VAICOM Community Edition](https://github.com/Penecruz/VAICOM-Community) — Free continuation of VAICOM PRO: voice control of comms, ATC, AWACS, wingmen and JTAC (★224)
- [VIRPIL Controls](https://virpil-controls.eu/) `[paid]` — Modular HOTAS and collective controllers widely used in the DCS community
- [VKB Sim](https://vkb-sim.pro/) `[paid]` — HOTAS sticks (Gunfighter, Gladiator) with precision sensors
- [VoiceAttack](https://voiceattack.com/) `[paid]` — Voice-command engine driving DCS radio menus, cockpit switches and macros; free tier capped at 20 commands
- [VPforce TelemFFB](https://github.com/walmis/VPforce-TelemFFB) — Drives force-feedback sticks from DCS telemetry: engine rumble, gunfire, ETL shake, dynamic springs (★83)
- [WhisperAttack](https://github.com/nikoelt/WhisperAttack) — Offline GPU Whisper speech recognition feeding VoiceAttack and VAICOM; replaces Windows speech recognition (★53)
- [WINCTRL (ex-Winwing)](https://winctrl.com/) `[paid]` — Module-specific panel replicas: F/A-18C, F-16C CDU, AH-64D EUFD; rebranded from WINWING in 2026

---

## Customization

### Mod Management

- [Better Mod.Manager](https://github.com/FreeProject089/BetterModsManager) — DCS mod manager with profiles, conflict detection and OvGME library import (★17)
- [DCS Updater / Launcher GUI](https://forum.dcs.world/topic/134493-the-dcs-updater-launcher-gui-utility-version-20-2023/) — Front end for the DCS updater: multiple installs, branches, repair, clean, launch profiles
- [FlightDeck](https://github.com/Rinzller/FlightDeck) — DCS launcher: updates, shader cache clearing, kneeboard manager, module moves via symlinks, OMM mod installs (★27)
- [Open Mod Manager](https://github.com/iquercorb/OpenModMan) — Open-source generic mod manager: install, toggle, and back up mods safely
- [SLAM](https://github.com/halfmanbear/SLAM) — Symlink-based PowerShell mod manager: enable or disable mods instantly without copying files

### Skins & Liveries

- [AMD Compressonator](https://github.com/GPUOpen-Tools/Compressonator) `[inactive]` — Standalone DDS conversion and compression toolbox
- [ED Livery Search](https://files.digitalcombatsimulator.com/en/files/filter/type-is-livery/apply/) — Community livery search by aircraft on the official site
- [Hoggit Wiki — Liveries](https://wiki.hoggitworld.com/view/Liveries) — Livery folder names per aircraft and how to unlock country-restricted liveries
- [Livery Link](https://github.com/Camble/LiveryLink) — Graphical livery manager: install from ED User Files, Google Drive or disk; imports existing liveries (★15)
- [NVIDIA Texture Tools Exporter](https://developer.nvidia.com/texture-tools-exporter) — DDS export and normal-map generation for Photoshop or standalone
- [VAT Skyline Updater](https://forum.dcs.world/topic/282485-vat-skyline-updater) `[inactive]` — Catalog client that installs and updates mods, liveries and joystick profiles per DCS install; account required

### Graphics Mods

- [ATMOS-X](https://www.atx4dcs.com/) — bandit648's successor to his Weather Mod: cloud and cirrus presets, aurora, METAR builder; breaks MP integrity check
- [DCS Optimized Textures](https://forum.dcs.world/topic/323252-dcs-optimized-textures/) `[inactive]` — Taz1004's re-compressed core textures; cuts install size by ~26 GB and lowers VRAM use
- [HMB NODPack](https://files.digitalcombatsimulator.com/en/files/3345896/) — NVG replacement with fullscreen or circular mask, P45/P43/P22 phosphor presets and reworked tube grain
- [ReShade](https://reshade.me/) — Post-processing injector; SMAA, AO, color grading, sharpening
- [Reshade VREM2](https://github.com/lefufu/DCS-world-reshade-VREM2) — DCS-specific sharpening addon for VR; integrity-check safe

---

## Aircraft & Content Mods

Community content mods (flyable aircraft, AI units, weapons, sounds). For mods whose download is a direct file host (Google Drive, MEGA, Dropbox), the link points to the ED forum thread for context.

### Aircraft Mods

- [AH-6J Little Bird (Helicopter EFM Demo)](https://github.com/CrudeCoder1/Helicopter-EFM-Demo) `[WIP]` — Free flyable AH-6J Little Bird built as a helicopter EFM demo; ARC-182 radio, armament panel, radar altimeter
- [C-130J Super Hercules (Anubis)](https://forum.dcs.world/topic/252075-dcs-super-hercules-mod-by-anubis/) `[inactive]` — Free flyable Hercules: clickable cockpit, custom flight model, ramp, 4 crew seats
- [Community J-10A](https://github.com/whisky-actual/Community-J-10) — Free community J-10A with clickable cockpit and custom avionics; by the Community Gripen author (★40)
- [Community JAS-39C Gripen](https://github.com/whisky-actual/Community-JAS-39-C) — Free community Gripen mod with clickable cockpit and custom avionics; among the most-flown mods (★240)
- [ED Forums — Flyable/Drivable Mods](https://forum.dcs.world/forum/1155-flyabledrivable-mods-for-dcs-world/) — Official forum section where community flyable aircraft mods are released and supported
- [F-15C Cockpit Overhaul](https://forum.dcs.world/topic/316347-f-15c-cockpit-overhaul-hotfix-23022024) `[inactive]` — Retextured F-15C cockpit with fixed instrument illumination
- [F-22A Raptor (Grinnelli Designs)](https://github.com/grinnellidesigns/f-22a) `[inactive]` — Free F-22A with EFM thrust vectoring, 6-DOF clickable cockpit and custom MFD pages; needs F-15C or Flaming Cliffs (★92)
- [F-23A Spectre (ThunderStruck Simulations)](https://github.com/ThunderStruck-Simulations/F-23A-Spectre-Mod) `[inactive]` — Free flyable what-if F-23A with clickable cockpit and SFM; requires the F-15C from Flaming Cliffs (★36)
- [F/A-18C Modern MPD](https://files.digitalcombatsimulator.com/en/files/3336864/) — Modernized Hornet MPDs: white symbology, color-coded SA and radar tracks, colored HSI, optional JHMCS II
- [Flaming Cliffs: Clickable Cockpits Continued](https://github.com/TicTac-93/FC-Clickable-Cockpits-Continued) — Basic clickable cockpits for all Flaming Cliffs and FC24 aircraft; passes integrity check (★27)
- [MH-60R Seahawk (Tanuki44)](https://forum.dcs.world/topic/385987-mh-60r-update-v4x/) — Free flyable MH-60R with sonobuoys, dipping sonar and anti-submarine warfare systems
- [Modern F-15E Mod](https://github.com/65thhaack/Modern-F15E-Mod) — Adds a SIT page and an HMD to the DCS F-15E Strike Eagle (★37)
- [OV-10A Bronco (Split Air)](https://forum.dcs.world/topic/307951-ov-10a-bronco-mod-by-split-air-teamand-more/) — Free flyable OV-10A light-attack and FAC aircraft; Split Air stopped development in 2026 after final hotfixes
- [Saab SK60 Mod (BAAS Dynamic)](https://github.com/BAAS-Dynamic/DCS-SK60-Mod) — Free flyable Saab 105/SK60 jet trainer with EFM, NS430 navigation, EADI/EHSI and basic weapons (★53)
- [Su-30 Community Mod](https://forum.dcs.world/topic/247098-dcs-su-30mk-mod/) — Free flyable Su-30 family (MKI, MKA, SM) with custom EFM and an optional Cockpit Weapon System (CWS) add-on
- [The Concorde](https://forum.dcs.world/topic/326601-the-concorde) `[inactive]` — Free flyable Concorde mod; OvGME and Saved Games ready
- [UH-60L Black Hawk Mod](https://forum.dcs.world/topic/293813-uh-60l-black-hawk-mod-official-thread/) — Free flyable UH-60L with clickable cockpit, cargo hauling and an armed Direct Action Penetrator variant
- [VSN EA-6B Prowler](https://forum.dcs.world/topic/256589-vsn-northrop-grumman-ea-6b-prowler) `[inactive]` — AI-only VSN Northrop Grumman EA-6B Prowler electronic-warfare aircraft with ALQ-99 jamming pods
- [VSN Flyable Aircraft Mods](https://forum.dcs.world/topic/147247-vsn-flyable-aircraft-mods/) — Hub thread for VSN's free flyable jets with FC-style avionics (F-104, F-4B/C, F/A-18D and more)

### Asset & Unit Packs

- [Cold War Assets Mod](https://forum.dcs.world/topic/350021-cold-war-assets-mod-v-12/) `[inactive]` — AI Tu-95K, Tu-126 AWACS, Tu-128, B-58 Hustler, Yak-28 and period missiles for Cold War scenarios
- [Complete Modern Chinese Military Mod](https://github.com/liwenHAO5105/DCS) `[inactive]` — Collected modern Chinese aircraft, vehicle, and ship asset packs in one place
- [Currenthill Military Assets](https://www.currenthill.com/) — Free modern military asset packs for the USA, UK, Germany, Sweden, Russia, Ukraine, China, Iran and Turkey
- [DCS Beacons and ICLS Mod](https://github.com/madmoney99/DCS-Beacon-and-ICLS-Mod) — Adds TACAN/VORTAC beacons and ICLS to ILS airfields on most maps for Hornet/Tomcat approaches; not IC-safe (★16)
- [DCS Lancaster (Tallboy Sims)](https://www.tallboy-sims.com/) — AI Avro Lancaster with Tallboy, Grand Slam and Upkeep loadouts, turret gunners and wing flex; regular RC updates
- [HighDigitSAMs Ultimate Compilation](https://github.com/dcs-sams/HighDigitSAMs-Ultimate-Compilation) — Maintained HighDigitSAMs fork merged with SAM Sites Asset Pack and IDF assets: SAM fixes, new missiles, Skynet support
- [Infantry - Animated Pilot Mod](https://forum.dcs.world/topic/196334-infantry-unit-animated-pilot-mod) `[inactive]` — Adds animated infantry and downed-pilot static and AI units
- [Markindel's PBY Catalina](https://forum.dcs.world/topic/292737-markindels-pby-catalina-torpedo-bomber) `[inactive]` — AI PBY Catalina torpedo bomber
- [Markindel's USS Iowa](https://forum.dcs.world/topic/277762-markindels-uss-iowa-late-war-vietnamkorea) `[inactive]` — AI USS Iowa-class battleship in late-war Vietnam/Korea fit
- [Massun92's Asset Pack](https://forum.dcs.world/topic/316316-massun92s-asset-pack-official-update-september-2026/) — Animated ground crew, M151A2 jeeps and airbase props; v1 of the pack was adopted into core DCS
- [SAM Sites Asset Pack](https://forum.dcs.world/topic/275571-sam-sites-asset-pack-a-3d-assets-mod-to-populate-you-sam-sites-farp-and-other-bases) `[inactive]` — IC-compliant 3D assets to populate SAM sites, FARPs, and bases
- [TeTeT's Vietnam War Vessels](https://github.com/tspindler-cms/tetet-vwv) — Vietnam-era naval and air assets: Essex and Sumner classes, USS New Jersey, PBR, F-8, MiG-17F (★18)
- [WWII Axis Naval Assets](https://forum.dcs.world/topic/259934-wwii-axis-naval-assets) `[inactive]` — AI WWII Axis naval vessels (Kriegsmarine)
- [WWII Pacific Allied Assets](https://forum.dcs.world/topic/263743-wwii-pacific-allied-assets) `[inactive]` — AI WWII Pacific Allied ships and assets

### Weapon Mods

- [7heAngryVe7eran's Weapon Mods](https://www.7heangryve7eran.com/dcs) — Non-authentic mods adding AIM-120, AIM-174B, Meteor, Maverick and HARM to the F-14, and AIM-174B to the F-16 and F/A-18
- [EU+US Weapons for JF-17](https://files.digitalcombatsimulator.com/en/files/3345045/) — Non-authentic fun mod adding EU and US weapons to the JF-17
- [Modern F-14 Weapons Pack](https://files.digitalcombatsimulator.com/en/files/3326478/) — Non-authentic mod adding AIM-9X, AIM-120, JDAM, HARM, Harpoon, Maverick and AIM-174B to the F-14, incl. F-14B(U)
- [The Definitive AMRAAM Mod](https://files.digitalcombatsimulator.com/en/files/3350446/) — Adds AIM-120C-5/C-7/D-3, AIM-174B, and AIM-260 to compatible aircraft

### Sound Mods

- [Echo 19](https://shop.echo19audio.com/en-eur/pages/dcs-addons) — Sound rework for the F/A-18, F-16, Mustang, Spitfire and DCS core
- [Skullz Genuine Huey Sound Mod](https://forum.dcs.world/topic/134264-skullz-genuine-huey-sound-mod) `[inactive]` — Realistic UH-1H Huey engine and rotor sound replacement

---

## Module-Specific Resources

### F/A-18C Hornet
- [Chuck's F/A-18C Guide](https://chucksguides.com/aircraft/dcs/fa-18c/) — Radar, TPOD, JDAM, JSOW, UFC procedures
- [Hoggit Carrier Operations Guide](https://wiki.hoggitworld.com/view/Carrier_Air_Operations) — CASE I/II/III patterns, ICLS setup, LSO grading

### F-16C Viper
- [Chuck's F-16C Guide](https://chucksguides.com/aircraft/dcs/f-16cm/) — DTC, SMS, HSD, FCR, HARM procedures

### A-10C II Warthog
- [Chuck's A-10C Guide](https://chucksguides.com/aircraft/dcs/a-10c/) — CDU, TAD, TGP, Maverick, gun

### F-14 Tomcat (Heatblur)
- [Heatblur Discord](https://discord.com/invite/heatblur-simulations) — Official Heatblur server; F-14, F-4E support and dev updates
- [Heatblur F-14 Manual](https://f14.manuals.heatblur.se/) — Full module manual covering pilot, RIO, and Jester AI
- [Jester AI Reference](https://f14.manuals.heatblur.se/f14ab/jester_iceman/overview.html) — Jester and Iceman AI crew reference, including the command wheel

### AH-64D Apache
- [Chuck's AH-64D Guide](https://chucksguides.com/aircraft/dcs/ah-64d/) — Startup, PNVS/TADS, CPG workflows, George AI

### Supercarrier
- [Hoggit Carrier Operations Guide](https://wiki.hoggitworld.com/view/Carrier_Air_Operations) — CASE I/II/III, ICLS, LSO grading
- [MOOSE AirBoss](https://flightcontrol-master.github.io/MOOSE_DOCS/Documentation/Ops.Airboss.html) — Scripted LSO grading, recovery tanker management, carrier ATC

---

## Communities & Events

### Communities

- [AMVI](https://www.amvi.it/) — Italian-speaking virtual air force since 2000: F-16, F/A-18, A-10C, AH-64 and warbird squadrons, flight academy, GCI
- [Bratskie Krylya](https://aviabk.ru/) — Russian-speaking DCS community (Братские крылья): public servers with player stats, ~2.2k-member Discord
- [Bullseye Francophone](https://bullseye-francophone.fr/) — French-speaking DCS community: co-op flights, BFM/BVR tournaments, dedicated server
- [Check-Six Forums](https://www.checksix-forums.com/) — Longstanding French sim forum with an active DCS section
- [Check-Six.fr](https://www.checksix-fr.com/category/dcs-world/) — French DCS news: module tests, guides, community events
- [Commus DCS FR](https://commus.kerboul.me) — French-language directory of DCS squadrons and communities; find your escadron
- [DCS Deutschland](https://discord.gg/dcsdeutschland) — German-speaking DCS community hub on Discord (~2.5k members): squadrons, help, joint flights
- [DCS Modding Hub](https://discord.gg/DugZsx6) — Discord community for DCS mod creators: aircraft, assets, skins, and scripting
- [DCS World 1st JTWF](https://cafe.naver.com/dcstr) — Main Korean DCS community since 2008 (~14k members): Naver Cafe with virtual wings, multiplayer and news
- [DCS World Wiki (Japanese)](https://wikiwiki.jp/dcs-world/) — Japanese community wiki: module pages, tutorials, multiplayer and mission editor notes
- [Eagle Dynamics Discord](https://discord.gg/eagledynamics) — Official ED server for announcements and community discussion
- [ED Forums — Squadrons](https://forum.dcs.world/clubs/) — Official ED forum directory of ~650 virtual squadrons, open or closed; the place to find a unit to fly with
- [Gildia.org](https://gildia.org/) — Polish DCS community hub: forum, wiki, Discord and dedicated servers with LotATC/Tacview; several squadrons
- [Hoggit Discord](https://discord.gg/hoggit) — ~35k members; help channels, module voice, weekly multiplayer sessions
- [Mudspike Forums](https://forums.mudspike.com/) — Multi-sim community with DCS discussions, AARs, hardware threads
- [r/hoggit](https://www.reddit.com/r/hoggit/) — Main DCS subreddit: discussions, screenshots, news, module debates
- [TAW DCS Division](https://tawdcs.org/) — The Art of Warfare's 100+ member DCS community; NA and EU battalions fly weekly PvP/PvE campaigns
- [VEAF](https://www.veaf.org/) — French DCS community behind the VEAF Mission Creation Tools; regular events and campaigns

### Content Creators

- [104th Maverick](https://www.youtube.com/@104thMaverick) — PvP gameplay, tactics, and debriefs on the 104th Phoenix server
- [Casmo](https://www.youtube.com/@CasmoTV) — Real-world Apache and Kiowa pilot; AH-64D systems, gunnery and tactics from operational experience
- [Grim Reapers](https://www.youtube.com/@GrimReapers) — Highest-volume DCS channel (~460k subscribers): controls, tutorials, online combat
- [Growling Sidewinder](https://www.youtube.com/@GrowlingSidewinder) — BFM tactics, Tacview debriefs, module reviews, PvP gameplay (500k+ subscribers)
- [Jabbers](https://www.youtube.com/@Jabbers) `[inactive]` — Carrier landings, hardware reviews, beginner tips
- [Matt Wagner](https://www.youtube.com/@MattWagner) — Late ED senior producer (1968–2026); archive of module feature previews and system walkthroughs
- [Ralfidude](https://www.youtube.com/@Ralfidude) — Combat footage with commentary; known for the Ralf-cam
- [Redkite](https://www.youtube.com/@RedKiteRender) `[inactive]` — Advanced systems tutorials, realism-focused
- [Reflected Simulations](https://www.youtube.com/@ReflectedSimulations) — Campaign developer; historical content and mission design insights
- [Spud Spike](https://www.youtube.com/@Spudspike) — Formerly Spudknocker; aircraft tutorials, historical content and multiplayer ops

### News & Media

- [FSElite — DCS News](https://fselite.net/simulator/dcs/) — Flight sim news site with regular DCS coverage
- [Mudspike](https://forums.mudspike.com/c/articles/5) `[inactive]` — Multi-sim article archive with DCS reviews, guides, and AARs, now hosted on the forums
- [Stormbirds](https://stormbirds.blog/) — DCS news and dev update commentary; active since 2016

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Quick rules:
- `[Name](url) — one-line description, no trailing period`
- `[inactive]` · `[paid]` · `[WIP]` badges where applicable
- Alphabetical order within each section
- Links verified, descriptions under 120 characters
