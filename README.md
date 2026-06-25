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

- [DCS World — Official Site](https://www.digitalcombatsimulator.com/en/) — Start here: downloads, news, module store, and user files
- [DCS World Steam Edition](https://store.steampowered.com/app/223750/DCS_World_Steam_Edition/) — Free on Steam; Caucasus map and two aircraft included
- [ED Forums](https://forum.dcs.world/) — Official forum; module bug reports, changelogs, and technical discussions
- [Eagle Dynamics Discord](https://discord.gg/eagledynamics) — Official ED Discord for announcements and community chat
- [Hoggit Discord](https://discord.gg/hoggit) — ~35k members; module help channels and weekly open multiplayer sessions
- [Hoggit DCS World Wiki](https://wiki.hoggitworld.com/view/Hoggit_DCS_World_Wiki) — The community wiki: aircraft systems, scripting, peripherals, multiplayer setup

### Free Modules

DCS World ships with two permanently free aircraft. Most paid modules also offer a 14-day free trial via the Module Manager.

- [A-4E-C Skyhawk](https://github.com/Community-A-4E/community-a4e-c) — Community-built carrier-capable Skyhawk with clickable cockpit, custom flight model, and air-to-ground radar; free and open source
- [Su-25T Frogfoot](https://www.digitalcombatsimulator.com/en/shop/modules/su-25t/) — Free ground-attack aircraft included with the base game; good first module for learning weapons employment
- [TF-51D Mustang](https://www.digitalcombatsimulator.com/en/shop/modules/tf-51d/) — Free unarmed trainer based on the P-51D; recommended for learning basic flight and aerobatics
- [VNAO T-45C Goshawk](https://forum.dcs.world/topic/203816-vnao-t-45-goshawk/) — Free community naval jet trainer with clickable cockpit and carrier ops support; made by Virtual Naval Air Operations
- [Free Trial System](https://www.digitalcombatsimulator.com/en/shop/modules/) — Most paid modules can be trialed for 14 days via the in-game Module Manager; no purchase required

> Note: community aircraft mods (A-4E-C, T-45C) may not be available on multiplayer servers running strict integrity check.

---

## Official Resources

- [DCS World — Documentation](https://www.digitalcombatsimulator.com/en/downloads/documentation/) — Free PDF manuals for every module
- [DCS World — E-Shop](https://www.digitalcombatsimulator.com/en/shop/) `[paid]` — Modules, terrains, campaigns, and bundles from ED
- [DCS World — Texture Templates](https://www.digitalcombatsimulator.com/en/downloads/texture_templates/) — Official PSD/TGA paint kits for most aircraft
- [DCS World — User Files](https://www.digitalcombatsimulator.com/en/files/) — Community missions, liveries, mods, kneeboards, campaigns
- [Eagle Dynamics YouTube](https://www.youtube.com/@EagleDynamicsTV) — Trailers, dev updates, and tutorials from ED

---

## Guides & Manuals

- [Chuck's Guides](https://chucksguides.com/) — Illustrated guides for almost every module: startup, systems, weapons, navigation
- [DCShelin](https://dcshelin.github.io/) — Community Michelin-style ratings for modules, terrains, and campaigns
- [ED Forums — Guides & Tutorials](https://forum.dcs.world/forum/42-guides-amp-tutorials/) — Community tutorials section on the official forum
- [Heatblur F-14 Manual](https://www.heatblur.se/F-14Manual/) — The F-14A/B online manual; covers pilot seat, RIO station, and Jester AI
- [Hoggit Wiki — Guides](https://wiki.hoggitworld.com/view/Guides) — BFM, carrier ops, peripherals, scripting
- [TAW Radar Simulator](https://tawdcs.org/radar-f15/) — Browser-based F-15 radar trainer; good starting point before going BVR online

---

## Scripting & Development

### Frameworks

- [MIST — Mission Scripting Tools](https://github.com/mrSkortch/MissionScriptingTools) `[inactive]` — Lightweight Lua utility library; still the standard dependency for CTLD, CSAR, and many community scripts (★200+)
- [MIST Documentation — Hoggit Wiki](https://wiki.hoggitworld.com/view/Mission_Scripting_Tools_Documentation) — MIST API reference
- [MOOSE](https://github.com/FlightControl-Master/MOOSE) — Massive OOP Lua framework: AI dispatchers, ATIS, MANTIS IADS, CTLD, CSAR, AirBoss… (★600+)
- [MOOSE Documentation](https://flightcontrol-master.github.io/MOOSE/) — Auto-generated reference for all MOOSE classes and methods
- [pydcs](https://github.com/pydcs/dcs) — Generate and edit `.miz` files from Python; powers DCS Liberation and Retribution (★183)
- [VEAF Mission Creation Tools](https://github.com/VEAF/VEAF-Mission-Creation-Tools) — Lua + Node.js for git-versioned DCS missions with dynamic spawning, ATIS, and radio menus (★25)
- [VEAF Documentation](https://veaf.github.io/documentation/) — VEAF scripting reference

### Mission Utilities

- [CSAR — Combat Search and Rescue](https://github.com/ciribob/DCS-CSAR) `[inactive]` — Rescues ejected pilots and delivers them to a friendly FARP; requires MIST
- [CTLD — Complete Troops & Logistics Deployment](https://github.com/ciribob/DCS-CTLD) — Helicopter troop transport, sling-load logistics, FARP construction, JTAC
- [DATIS — DCS ATIS via SRS](https://github.com/rkusa/DATIS) — Generates spoken ATIS over SRS using in-mission weather; supports AWS Polly and Google TTS (★100+)
- [JTAC AutoLaze](https://github.com/ciribob/DCS-JTACAutoLaze) `[inactive]` — Auto-lasing JTAC script; functionality absorbed into DCS Liberation
- [Splash Damage Script](https://github.com/stephenpostlethwaite/DCSSplashDamageScript) — TNT-equivalent blast modelling, napalm, WP, and secondary effects for DCS explosions

### Dynamic Campaigns

- [DCE — Dynamic Campaign Engine](https://github.com/bbirchnz/dce-campaign-builder) — Community builder for the original MBot/Minsky persistent turn-by-turn campaign engine
- [DCT — Dynamic Campaign Tools](https://github.com/jtoppins/dct) `[inactive]` — Lua framework for persistent server-side campaigns; scenarios built from templates, no external program needed
- [DCT Documentation](https://jtoppins.github.io/dct/) — Full docs and quick-start for DCT
- [DCS Liberation](https://github.com/dcs-liberation/dcs_liberation) — Turn-based SP/co-op dynamic campaign generator: persistent front-line, IADS, JTAC, SEAD (★778)
- [Pretense](https://github.com/GoldJohnKing/pretense) `[inactive]` — In-mission sandbox: mercenary economy, AI logistics, XP progression, persistence
- [Retribution](https://github.com/dcs-retribution/dcs-retribution) — Active Liberation fork; adds Splash Damage, CTLD, improved front-line mechanics (★158)

### Developer Tools

- [DCS-BIOS](https://github.com/DCS-Skunkworks/dcs-bios) — Exports cockpit state over serial/UDP; the base layer for physical panel integration (★406)
- [DCS-BIOS Arduino Library](https://github.com/DCS-Skunkworks/dcs-bios-arduino-library) — Arduino/ESP32 client library for DCS-BIOS (★69)
- [DCS-fiddle](https://github.com/flying-dice/dcs-fiddle) — Browser-based DCS Lua REPL; test scripts without restarting the mission
- [DCS-gRPC Go bindings](https://github.com/DCS-gRPC/go-bindings) — Go protobuf/gRPC bindings for the DCS-gRPC API
- [DCS-gRPC Python bindings](https://github.com/DCS-gRPC/python-bindings) — Auto-generated Python stubs for the DCS-gRPC API
- [DCS-gRPC rust-server](https://github.com/DCS-gRPC/rust-server) — Rust gRPC server embedded in DCS; exposes mission events and commands to external clients (★101)
- [DCS Lua Debug Adapter](https://github.com/applevangelist/DCS-Lua-Debugger) — VSCode debug adapter for Lua running inside DCS missions
- [DCS Scratchpad](https://github.com/rkusa/dcs-scratchpad) — In-game scratchpad overlay for notes and coordinates (★200)
- [Hoggit DCS SSE Wiki](https://wiki.hoggitworld.com/view/Simulator_Scripting_Engine_Documentation) — Reference for the in-game Lua scripting environment: functions, classes, callbacks
- [Quaggles DCS Input Command Injector](https://github.com/Quaggles/dcs-input-command-injector) — Adds custom per-aircraft keybinds that survive updates without editing default input Lua
- [Skynet-IADS](https://github.com/walder/Skynet-IADS) — EWR stations datalink SAM sites; SAMs go cold on HARM detection (★218)
- [skyeye](https://github.com/dharmab/skyeye) — Self-hosted AI GCI bot with voice recognition and neural TTS; runs over SRS and DCS-gRPC (★400+)
- [Tacview ACMI SDK](https://www.tacview.net/documentation/acmi/en/) — ACMI format spec and SDK for building Tacview-compatible exporters
- [Twitch2DCS](https://github.com/rthom91/twitch2dcs) — Shows Twitch chat inside DCS so VR streamers can read it without removing the headset

---

## Mission Design

### Mission Generators

- [BriefingRoom for DCS](https://github.com/DCS-BR-Tools/briefing-room-for-dcs) — GUI/CLI generator producing SP/MP `.miz` files in seconds; custom templates, scripted SAMs and JTAC (★294)
- [CombatFlite](https://www.combatflite.com/) `[paid]` — Mission planner with DCS export, briefing packs, kneeboard cards, and airspace deconfliction
- [DCS Real Weather](https://github.com/evogelsa/dcs-real-weather) — Fetches a live METAR and patches the weather block in a `.miz` before server restart (★32)
- [DCS WeatherInjector](https://github.com/destotelhorus/DCS-WeatherInjector) — CLI/scheduled METAR and datetime injection for dedicated servers
- [VEAF Mission Converter](https://github.com/VEAF/VEAF-mission-converter) — Unpacks a `.miz` into a versionable folder, edit, then rebuild with VEAF scripts injected
- [DCS Web Editor](https://dcs-web-editor.vercel.app/user) Free mission editor that works in the browser, multi drag & select, copy/paste, undo/redo, and easy porting of missions to different theaters.

### Planning Tools

- [MizMap](https://github.com/mizmap/mizmap) — Live browser map for mission creators; place and track units in real time while building
- [DCS Web Planner](https://dcs-web-editor.github.io/dcs-web-viewer-deploy/) Free mission planner that works in the browser without installation. Includes kneeboard generator, DTC export/import and more
- [DCS Planner](https://dcsplanner.com/) - A website to plan your mission stear points, geolines, drawing and more

### Training Missions

- [Bandit on Demand](https://www.digitalcombatsimulator.com/en/files/3320850/) — BFM/BVR SP/MP mission; spawn any AI aircraft type via voice command or F10 menu
- [BFM Gun-only Practice v2.1](https://www.digitalcombatsimulator.com/en/files/3325527/) — 1v1 cannon-only BFM on Caucasus and Marianas
- [Caucasus Training Map by NZArmA](https://www.digitalcombatsimulator.com/en/files/3319714/) — AAR, interception, escort, mobile targets, JTAC, SAM — all in one mission
- [DCS OVERLOAD Caucasus](https://github.com/srogers909/DCS_OVERLOAD_Caucasus) — Air-to-air training with respawning aggressors, situational awareness focus
- [Hoggit Training Server](https://wiki.hoggitworld.com/view/Hoggit_Training_Server) — 24/7 community training server on Caucasus with airfields, SAM threats, and range targets
- [Through the Inferno](https://www.throughtheinferno.com/) — Dynamic action and training missions with randomized spawns, objectives, and JTAC, for SP and co-op on many maps

### Third-Party Campaigns

- [Baltic Dragon Campaigns](https://www.digitalcombatsimulator.com/en/shop/campaigns/?CREATOR=Baltic+Dragon) `[paid]` — Raven One, The Gamblers, The Rampagers, Arctic Thunder; extensive voice work
- [Bunyap Campaigns](https://www.digitalcombatsimulator.com/en/shop/campaigns/?CREATOR=Bunyap+Campaigns) `[paid]` — A-10C II and F/A-18C campaigns; authentic CAS and SEAD scenarios
- [Free Community Campaigns](https://www.digitalcombatsimulator.com/en/files/filter/type-is-campaign/localization-is-english/apply/) — Hundreds of free player-made campaigns on ED User Files
- [Heatblur Speed and Angels](https://www.digitalcombatsimulator.com/en/shop/campaigns/dcs_f-14_speed_and_angels_campaign/) `[paid]` — F-14B campaign voiced by an actual US Navy RIO
- [Reflected Simulations](https://www.digitalcombatsimulator.com/en/shop/campaigns/?CREATOR=Reflected+Simulations) `[paid]` — WWII through modern campaigns (P-47, P-51, Spitfire, F/A-18C); known for writing and voice work

---

## Flight Analysis & Debriefing

- [Logbook](http://logbook.ansirial.it) — Automatically records single- and multiplayer flight history and career progress
- [SRS Recorder](https://github.com/wrycu/srs_recorder) — Records SRS radio transmissions timestamped alongside Tacview playback; requires DCS-gRPC
- [Tacview](https://www.tacview.net/) `[free-tier]` — 3D flight debrief tool; records to `.acmi`, shows radar picture, kill chains, telemetry
- [Tacview — DCS Integration Guide](https://www.tacview.net/documentation/dcs/) — How to enable the built-in Tacview recorder in DCS
- [Tacview 2.0 Preview](https://www.tacview.net/product/tacview2/en/) `[WIP]` — Next-gen rewrite: multi-viewport, real terrain, addon scripting

---

## Multiplayer

### Communication

- [DCSServerBot](https://github.com/Special-K-s-Flightsim-Bots/DCSServerBot) — Python/Discord bot for DCS server admin: stats, slot blocking, SRS/LotATC/Tacview/Olympus integrations, 30+ plugins (★300+)
- [SRS — SimpleRadioStandalone](https://github.com/ciribob/DCS-SimpleRadioStandalone) — Open-source VoIP radio tied to cockpit frequencies; present on almost every multiplayer server (★544)
- [SRS Website](https://dcssimpleradio.com/) — Official SRS homepage with one-click installer
- [UniversRadio](https://tacnoworld.fr/universradio/) — TeamSpeak-based radio sim; models range, terrain masking, modulation, and encryption

### Server Management

- [Aterfax/DCS-World-Dedicated-Server-Docker](https://github.com/Aterfax/DCS-World-Dedicated-Server-Docker) — Docker image for DCS World Server on Linux via Wine; companion images for Retribution, Olympus, DCSServerBot (★57)
- [dcs-server-wine](https://github.com/ActiumDev/dcs-server-wine) — Automated headless DCS + SRS install and management scripts for Linux; multi-instance support
- [DCS Dedicated Server — ED Guide](https://www.digitalcombatsimulator.com/en/support/faq/server/) — ED's official guide to setting up a headless DCS dedicated server
- [DCSServerBot](https://github.com/Special-K-s-Flightsim-Bots/DCSServerBot) — See Communication; also handles server admin, slot blocking, weather injection, extension management
- [DCSOlympus](https://github.com/Pax1601/DCSOlympus) — Real-time RTS map control: spawn, task, and remove units on a live server via web map; Blue/Red GM modes (★347)
- [Perun](https://github.com/szporwolik/perun) `[inactive]` — Lua plugin exporting sim data to MySQL; merges SRS and LotATC for unified analytics dashboards

### Tactical Awareness

- [DCSOlympus](https://github.com/Pax1601/DCSOlympus) — Live map showing all coalition units; coalition view can be restricted for realistic ops
- [LotATC](https://www.lotatc.com/) `[paid]` — GCI/ATC radar client+server with realistic radar coverage, IFF, and BRAA tools; integrates with SRS
- [LotATC — Hoggit Wiki](https://wiki.hoggitworld.com/view/LotATC) — How to connect to a LotATC server and perform GCI
- [skyeye](https://github.com/dharmab/skyeye) — Self-hosted AI GCI bot; handles PICTURE, BOGEY DOPE, DECLARE, SPIKED calls over SRS (★400+)
- [Sneaker — WebGCI](https://github.com/Aterfax/sneaker) — Web-based GCI situational awareness dashboard pulling from DCS-gRPC

### AI / ATC / IADS

- [AI_ATC Nellis AFB](https://github.com/Avalanche110/AI_ATC_Nellis_AFB) — Script adding AI-controlled ATC and ground traffic to Nellis AFB
- [DATIS](https://github.com/rkusa/DATIS) — Generates airfield and carrier ATIS broadcasts over SRS from in-mission weather (★100+)
- [DCS AI REVAMP](https://forum.dcs.world/topic/383084-dcs-ai-revamp-a-dynamic-battlefield-and-advanced-ground-ai-system) `[WIP]` — Scripted dynamic battlefield with smarter, more reactive ground AI
- [MOOSE AirBoss](https://flightcontrol-master.github.io/MOOSE_DOCS/Documentation/Ops.AirBoss.html) — Scripted LSO grading, recovery tanker management, and carrier ATC
- [MOOSE MANTIS](https://flightcontrol-master.github.io/MOOSE_DOCS/Documentation/Ops.MANTIS.html) — EWR-controlled SAM management; compatible with Skynet-IADS behavior
- [Skynet-IADS](https://github.com/walder/Skynet-IADS) — The reference IADS script: EWR datalinks SAM sites, SAMs go cold on HARM detection, supports HighDigitSAMs (★218)
- [skyeye](https://github.com/dharmab/skyeye) — Modern OverlordBot replacement; better speech recognition and correct brevity procedures (★400+)

---

## Notable Servers & Events

### Persistent Servers

- [4YA Servers](https://4ya.net/) — Multi-map PvE/PvP (Caucasus, WWII Normandy, others); 24/7
- [Blue Flag](https://blueflag.games/) — PvP dynamic campaign across multiple eras (Cold War, 80s, Modern)
- [DCS Server Tracker (Glowie)](https://dcs.glowie.xyz/servers) — Live public-server browser with player counts
- [DDCS — Dynamic DCS Server](https://ddcs.io/) — Long-running PvP server with economy and scoring system
- [Enigma's Cold War Campaign](https://forum.dcs.world/topic/287464-enigmas-dynamic-cold-war-campaign-pvppve-server/) — Cold War PvP/PvE (Caucasus/Syria) with sector attrition mechanics; [source on GitHub](https://github.com/Enigma1989YT/Enigma-Cold-War-V1-Public)
- [Growling Sidewinder Server](https://growlingsidewinder.com/) — High-population fast jet PvP; stats at stats.growlingsidewinder.com
- [Hoggit GAW — Georgia At War](https://wiki.hoggitworld.com/view/Hoggit_Georgia_At_War) — Hoggit's flagship Caucasus persistent server; new-pilot friendly
- [Hoggit PGAW — Persian Gulf At War](https://wiki.hoggitworld.com/view/Hoggit_Persian_Gulf_At_War) — GAW's Persian Gulf counterpart

### Events & Competitions

- [DCSWorldEvents](https://www.twitch.tv/dcsworldevents) — Runs SATAL, SATAL Cold War, AIR COMBAT, and charity events
- [SATAL — Simulated Air-to-Air League](https://www.satal.org/) — Competitive air-to-air DCS league with structured tournament brackets
- [Virtual Airshows](https://www.virtual-airshows.com/) — Organizer of Wings Over Tbilisi and other DCS virtual airshows

---

## Hardware & Cockpit Integration

### Cockpit Builders

- [BojoteX/CockpitOS](https://github.com/BojoteX/CockpitOS) — ESP32 firmware for DCS-BIOS panels; USB/Wi-Fi/BLE and TFT displays, no Arduino IDE needed
- [DCS-BIOS](https://github.com/DCS-Skunkworks/dcs-bios) — Exports cockpit state over serial/UDP; required by virtually every hardware integration tool (★406)
- [DCS-BIOS Arduino Library](https://github.com/DCS-Skunkworks/dcs-bios-arduino-library) — Arduino/ESP32 client library for DCS-BIOS panels (★69)
- [DCSFlightpanels](https://github.com/DCS-Skunkworks/DCSFlightpanels) — Saitek/Logitech panel and Stream Deck configurator via DCS-BIOS; supports Radio Panel sim and SRS PTT
- [ED Forums — Home Cockpits](https://forum.dcs.world/forum/181-home-cockpits) — The official forum section for simpit builds
- [Helios](https://github.com/HeliosVirtualCockpit/Helios) — Touchscreen virtual cockpit builder with per-aircraft profiles; communicates via exports.lua (★248)
- [Hoggit Wiki — DCS-BIOS / Cockpit Building](https://wiki.hoggitworld.com/view/DCS_Bios_/_Cockpit_Building) — Getting started with cockpit building and DCS-BIOS
- [Ikarus](https://github.com/s-d-a/Ikarus) — Virtual cockpit gauges on a secondary monitor or tablet via DCS ExportScript

### Kneeboard & Overlays

- [Capt Zeen Helios Profiles](http://www.captzeen.com/helios/profiles.asp) — Large library of Helios profiles with monitor configurations for many aircraft
- [DCS Kneeboard (iOS & Android)](https://forum.dcs.world/topic/256088-dcs-kneeboard-ios-android-app) — iOS and Android kneeboard app for flight plans, charts, and checklists
- [DCS Moving Map](https://movingmap.bergison.com) — Web and Android real-time moving map covering all DCS theaters
- [DCS Live Map](https://dcs-web-editor.github.io/dcs-web-viewer-deploy/live/) free moving map for OpenKneeboard or ingame browser, many options and layers
- [DCS SAM Threat Guide](https://www.digitalcombatsimulator.com/en/files/3331424) — Kneeboard reference for SAM systems, ranges, and threat recognition
- [DCS UFC X](https://github.com/pet333r/pw-dev_script) — Android touchscreen UFC/ICP panel app for data entry into DCS aircraft
- [DCS-ExportScripts](https://github.com/s-d-a/DCS-ExportScripts) — Export cockpit data to external displays, apps, and Ikarus gauges
- [DCS Interface for StreamDeck](https://github.com/charlestytler/streamdeck-dcs-interface) — Stream Deck plugin with DCS cockpit event bindings and state-driven button images
- [DCS:The Way](https://github.com/aronCiucu/DCSTheWay) — Companion app that pushes F10-map markpoints into the aircraft as steerpoints
- [Digital Kneeboard Simulator](https://www.digitalkneeboardsimulator.com/) — Web app for flight plans, loadouts, comm cards, and kneeboard export
- [GV5Js Datacard Generator](https://forum.dcs.world/topic/261081-gv5js-datacard-generator) — Generates printable mission datacards as DCS kneeboard pages
- [Kneeboard Builder](https://dcskneeboardbuilder.com/) — Converts PDFs to DCS kneeboard images; per-aircraft profile management
- [OpenKneeboard](https://github.com/OpenKneeboard/OpenKneeboard) — VR and 2D kneeboard overlay; graphics-tablet annotation, PDF nav, DCS radio log, HOTAS bindings (★334)
- [Shark Planner](https://github.com/okopanja/SharkPlanner) — Companion app that enters waypoints into the Ka-50 ABRIS/PVI-800 and other nav systems
- [Simtools.app](https://www.simtools.app) — Web app to build and download custom aircraft checklists and kneeboards
- [SlipHavoc DCS-Kneeboards](https://github.com/SlipHavoc/DCS-Kneeboards) — Pre-made kneeboard set covering most popular modules

### VR

- [DCS VR Optimization Guide](https://www.gamersbynight.com/dcs-settings-vr/) — Step-by-step for OpenXR, MT mode, and VR performance tuning in DCS 2.8+
- [fholger/vrperfkit](https://github.com/fholger/vrperfkit) `[inactive]` — FSR/NIS/CAS upscaling and foveated rendering for SteamVR/OpenVR (★1,400)
- [mbucchia/OpenXR-Toolkit](https://github.com/mbucchia/OpenXR-Toolkit) `[inactive]` — FSR/NIS upscaling, foveated rendering, and post-processing for OpenXR; development stopped April 2024
- [mbucchia/Quad-Views-Foveated](https://github.com/mbucchia/Quad-Views-Foveated) — OpenXR foveated rendering layer for Pimax Crystal, Quest Pro, and other eye-tracked headsets (★181)
- [OpenKneeboard](https://openkneeboard.com/) — See Kneeboard & Overlays; essential in-headset kneeboard overlay with tablet-pen support
- [OpenXR Toolkit Tuning Guide](https://forum.dcs.world/topic/296983-openxr-toolkit-tuning-guide-updated-210223/) — DCS-specific OpenXR Toolkit setup guide for `--force_OpenXR` + MT mode
- [Reshade VREM](https://github.com/lefufu/DCS-world-reshade-VREM) — DCS sharpening and visual enhancement Reshade addon; integrity-check safe
- [VR4DCS](https://vr4dcs.com/) — VR optimization reference: OS settings, SteamVR, reprojection, per-headset guides
- [VRLowdown — DCS on Meta Quest](https://vrlowdown.com/dcs-world-quest-2/) — DCS setup guide for Meta Quest (Air Link, Virtual Desktop, optimizations)

### Peripherals

- [AITrack](https://github.com/AIRLegend/aitrack) — Webcam face tracker feeding OpenTrack via neural net; low CPU, no IR hardware needed
- [Chuck's Guides — HOTAS Sections](https://chucksguides.com/) — Recommended HOTAS bindings for each module
- [ControllerBuddy](https://controllerbuddy.org/) — Game controller mapping tool for flight sims; profiles for most DCS modules (★168)
- [DCS Detent Calculator](https://github.com/asherao/DCS-Detent-Calculator) — Spreadsheet that finds throttle detent positions for afterburner and idle cutoff
- [DelanClip](https://delanclip.com/) `[paid]` — Affordable IR LED head-tracking clip; works with OpenTrack and TrackIR software
- [EyeTrackVR](https://github.com/EyeTrackVR/EyeTrackVR) — DIY open-source eye-tracking for VR headsets; ESP32 firmware + PC software
- [Hoggit Peripherals Guide](https://wiki.hoggitworld.com/view/Peripherals) — HOTAS, rudder pedals, head tracking, and VR setup for DCS
- [Joystick Diagrams](https://joystick-diagrams.com/) — Generates printable layout diagrams from your DCS bindings
- [OpenTrack](https://github.com/opentrack/opentrack) — Free head-tracking software; supports FaceTrackNoIR, Aruco, IR clip, FreeTrack output (★3,000+)
- [RS Mapper](https://forum.dcs.world/topic/175248-rs-mapper-release) `[inactive]` — Maps advanced HOTAS modes and shift states that DCS does not expose natively
- [VIRPIL Controls](https://virpil-controls.eu/) `[paid]` — Modular HOTAS and collective controllers widely used in the DCS community
- [VKB Sim](https://vkbcontrollers.com/) `[paid]` — HOTAS sticks (Gunfighter, Gladiator) with precision sensors
- [Winwing](https://en.winwingsim.com/) `[paid]` — Module-specific panel replicas: F/A-18C, F-16C CDU, AH-64D EUFD

---

## Customization

### Mod Management

- [Open Mod Manager](https://github.com/sedenion/OpenModMan) — Open-source generic mod manager: install, toggle, and back up mods safely

### Skins & Liveries

- [AMD Compressonator](https://github.com/GPUOpen-Tools/Compressonator) — Standalone DDS conversion and compression toolbox
- [ED Livery Search](https://www.digitalcombatsimulator.com/en/files/filter/type-is-livery/apply/) — Community livery search by aircraft on the official site
- [Hoggit Wiki — Liveries](https://wiki.hoggitworld.com/view/Liveries) — DCS livery folder structure, `description.lua`, and paint kit guide
- [NVIDIA Texture Tools Exporter](https://developer.nvidia.com/nvidia-texture-tools-exporter) — DDS export and normal-map generation for Photoshop or standalone
- [VAT Skyline Updater](https://forum.dcs.world/topic/282485-vat-skyline-updater) `[WIP]` — Keeps the VAT Skyline livery pack updated to the latest community versions

### Graphics Mods

- [ATMOS-X](https://www.atx4dcs.com/) — Weather enhancement mod adding volumetric cloud presets and thunderstorm effects; free, integrity-check safe
- [Custom NVGs via ReShade](https://flightsim.to/file/14860/night-vision-goggles) — ReShade preset for more realistic night-vision goggle rendering; integrity-check safe
- [ReShade](https://reshade.me/) — Post-processing injector; SMAA, AO, color grading, sharpening
- [Reshade VREM](https://github.com/lefufu/DCS-world-reshade-VREM) — DCS-specific sharpening addon for VR; integrity-check safe

---

## Aircraft & Content Mods

Community content mods (flyable aircraft, AI units, weapons, sounds). For mods whose download is a direct file host (Google Drive, MEGA, Dropbox), the link points to the ED forum thread for context.

### Aircraft Mods

- [F-15C Cockpit Overhaul](https://forum.dcs.world/topic/316347-f-15c-cockpit-overhaul-hotfix-23022024) — Retextured F-15C cockpit with fixed instrument illumination
- [The Concorde](https://forum.dcs.world/topic/326601-the-concorde) — Free flyable Concorde mod; OvGME and Saved Games ready
- [VSN EA-6B Prowler](https://forum.dcs.world/topic/256589-vsn-northrop-grumman-ea-6b-prowler) — Flyable VSN Northrop Grumman EA-6B Prowler mod

### Asset & Unit Packs

- [Complete Modern Chinese Military Mod](https://github.com/liwenHAO5105/DCS) — Collected modern Chinese aircraft, vehicle, and ship asset packs in one place
- [High Digit SAMs](https://github.com/Auranis/HighDigitSAMs) — IC-compliant asset pack adding many modern and historic air-defence systems
- [Infantry - Animated Pilot Mod](https://forum.dcs.world/topic/196334-infantry-unit-animated-pilot-mod) — Adds animated infantry and downed-pilot static and AI units
- [Markindel's PBY Catalina](https://forum.dcs.world/topic/292737-markindels-pby-catalina-torpedo-bomber) — AI PBY Catalina torpedo bomber
- [Markindel's USS Iowa](https://forum.dcs.world/topic/277762-markindels-uss-iowa-late-war-vietnamkorea) — AI USS Iowa-class battleship in late-war Vietnam/Korea fit
- [Ropucha-Class Landing Ship](https://forum.dcs.world/topic/199842-early-access-ropucha-class-soviet-landing-ship) `[WIP]` — AI Ropucha-class Soviet landing ship
- [SAM Sites Asset Pack](https://forum.dcs.world/topic/275571-sam-sites-asset-pack-a-3d-assets-mod-to-populate-you-sam-sites-farp-and-other-bases) — IC-compliant 3D assets to populate SAM sites, FARPs, and bases
- [WWII Axis Naval Assets](https://forum.dcs.world/topic/259934-wwii-axis-naval-assets) — AI WWII Axis naval vessels (Kriegsmarine)
- [WWII Pacific Allied Assets](https://forum.dcs.world/topic/263743-wwii-pacific-allied-assets) — AI WWII Pacific Allied ships and assets

### Weapon Mods

- [A2G/A2A Missile Tab](https://www.7heangryve7eran.com/dcs) `[WIP]` — Tweak that surfaces air-to-ground missiles in the air-to-air loadout tab
- [EU+US Weapons for JF-17](https://www.digitalcombatsimulator.com/en/files/3345045) — Non-authentic fun mod adding EU and US weapons to the JF-17
- [The Definitive AMRAAM Mod](https://www.digitalcombatsimulator.com/en/files/3350446) — Adds AIM-120C-5/C-7/D-3, AIM-174B, and AIM-260 to compatible aircraft

### Sound Mods

- [Skullz Genuine Huey Sound Mod](https://forum.dcs.world/topic/134264-skullz-genuine-huey-sound-mod) — Realistic UH-1H Huey engine and rotor sound replacement
- [Echo 19](https://shop.echo19audio.com/en-eur/pages/dcs-addons) - Sound rework for the F/A-18, F-16, Mustang, Spitfire and DCS core

---

## Module-Specific Resources

### F/A-18C Hornet
- [Chuck's F/A-18C Guide](https://chucksguides.com/aircraft/dcs/fa-18c/) — Radar, TPOD, JDAM, JSOW, UFC procedures
- [Hoggit Carrier Operations Guide](https://wiki.hoggitworld.com/view/Carrier_Operations) — CASE I/II/III patterns, ICLS setup, LSO grading

### F-16C Viper
- [Chuck's F-16C Guide](https://chucksguides.com/aircraft/dcs/f-16cm/) — DTC, SMS, HSD, FCR, HARM procedures

### A-10C II Warthog
- [Chuck's A-10C Guide](https://chucksguides.com/aircraft/dcs/a-10c/) — CDU, TAD, TGP, Maverick, gun

### F-14 Tomcat (Heatblur)
- [Heatblur Discord](https://discord.gg/heatblur) — Official Heatblur server; F-14, F-4E support and dev updates
- [Heatblur F-14 Manual](https://www.heatblur.se/F-14Manual/) — Full module manual covering pilot, RIO, and Jester AI
- [Jester AI Reference](https://www.heatblur.se/F-14Manual/jester/overview.html) — Jester command wheel reference and mission scripting hooks

### AH-64D Apache
- [Chuck's AH-64D Guide](https://chucksguides.com/aircraft/dcs/ah-64d/) — Startup, PNVS/TADS, CPG workflows, George AI
- [George AI TEDAC Guide — ED Forums](https://forum.dcs.world/topic/316879-george-ai-tedac/) — Community reference for using the George AI co-pilot

### Supercarrier
- [Hoggit Carrier Operations Guide](https://wiki.hoggitworld.com/view/Carrier_Operations) — CASE I/II/III, ICLS, LSO grading
- [MOOSE AirBoss](https://flightcontrol-master.github.io/MOOSE_DOCS/Documentation/Ops.AirBoss.html) — Scripted LSO grading, recovery tanker management, carrier ATC

---

## Communities & Events

### Communities

- [Bullseye Francophone](https://bullseye-francophone.fr/) — French-speaking DCS community: co-op flights, BFM/BVR tournaments, dedicated server
- [Check-Six Forums](https://www.checksix-forums.com/) — Longstanding French sim forum with an active DCS section
- [Check-Six.fr](https://www.checksix-fr.com/category/dcs-world/) — French DCS news: module tests, guides, community events
- [Commus DCS FR](https://commus.kerboul.me) — French-language directory of DCS squadrons and communities; find your escadron
- [DCS Modding Hub](https://discord.gg/DugZsx6) — Discord community for DCS mod creators: aircraft, assets, skins, and scripting
- [Eagle Dynamics Discord](https://discord.gg/eagledynamics) — Official ED server for announcements and community discussion
- [Hoggit Discord](https://discord.gg/hoggit) — ~35k members; help channels, module voice, weekly multiplayer sessions
- [Mudspike Forums](https://forums.mudspike.com/) — Multi-sim community with DCS discussions, AARs, hardware threads
- [r/hoggit](https://www.reddit.com/r/hoggit/) — Main DCS subreddit: discussions, screenshots, news, module debates
- [VEAF](https://www.veaf.org/) — French DCS community behind the VEAF Mission Creation Tools; regular events and campaigns

### Content Creators

- [104th Maverick](https://www.youtube.com/@104thMaverick) — PvP gameplay, tactics, and debriefs on the 104th Phoenix server
- [BuddySpike](https://www.youtube.com/@BuddySpike) — BVR/BFM tactics and weapons employment by module
- [Grim Reapers](https://www.youtube.com/@GrimReapers) — Highest-volume DCS channel (~1.5M subscribers): controls, tutorials, online combat
- [Growling Sidewinder](https://www.youtube.com/@GrowlingSidewinder) — BFM tactics, Tacview debriefs, module reviews, PvP gameplay (500k+ subscribers)
- [Jabbers](https://www.youtube.com/@Jabbers) — Carrier landings, hardware reviews, beginner tips
- [Matt Wagner](https://www.youtube.com/@MattWagner) — ED producer; dev update streams and early-access previews
- [Ralfidude](https://www.youtube.com/@Ralfidude) — Combat footage with commentary; known for the Ralf-cam
- [Redkite](https://www.youtube.com/@redkite81) — Advanced systems tutorials, realism-focused
- [Reflected Simulations](https://www.youtube.com/@ReflectedSimulations) — Campaign developer; historical content and mission design insights
- [Spudknocker](https://www.youtube.com/@Spudknocker) — DCS entertainment: aircraft tutorials and multiplayer ops

### News & Media

- [FSElite — DCS News](https://fselite.net/category/dcs-world/) — Flight sim news site with regular DCS coverage
- [Mudspike](https://mudspike.com/) — DCS articles, reviews, and AARs; also hosts Chuck's Guides
- [Stormbirds](https://stormbirds.blog/) — DCS news and dev update commentary; active since 2016

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Quick rules:
- `[Name](url) — one-line description, no trailing period`
- `[inactive]` · `[paid]` · `[WIP]` badges where applicable
- Alphabetical order within each section
- Links verified, descriptions under 120 characters
