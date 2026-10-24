---
name: HEAT Sentinel
description: The all-in-one stats and interface mod for WoT HEAT. Records every battle on its own and turns it into stats, player profiles, 1v1 rivalries, loadouts and Marks of Excellence, reworks the game's interface with custom sights, colours, a real map on the radar and team alerts, and adds a Tactics Board, replays and stream tools.
page-image: https://raw.githubusercontent.com/OxCone1/HEAT-Sentinel/main/heat-labs/banner.jpg
compatible-version: 1.2.2
status: Available # Available | Work in Progress | Beta Testing | Discontinued | Prototype | Unknown
category: Statistics, Interface, Visual # First category is primary, others are secondary: Gameplay | Interface | Audio | Visual | Model | Performance | Loader | Statistics
type: Closed Source # Open Source | Closed Source

downloads:
  layout: single # single | two | three | four
  links:
    - os: Windows
      url: https://github.com/OxCone1/HEAT-Sentinel/releases
    - os: MacOS
      url: URL
    - os: Linux
      url: URL

license:
  enabled: true
  name: Proprietary (free for personal use)
  url: https://github.com/OxCone1/HEAT-Sentinel/blob/main/COPYRIGHT.md

support:
  enabled: true
  description: Found a bug or want to ask for a feature? Open an issue on GitHub. For setup help, release news and sharing reticles or strategies, join the Discord server.
  feedback:
    enabled: true
    name: GitHub Issues
    url: https://github.com/OxCone1/HEAT-Sentinel/issues
  support:
    enabled: true
    name: Discord Server
    url: https://discord.gg/AjfcuhDDw5

features:
  enabled: true # Maximum of 4 feature cards. For icons use fontawesome icons only found here https://fontawesome.com/search?ic=free-collection
  cards:
    - enabled: true
      icon: <i class="fa-solid fa-chart-line"></i>
      name: Stats That Remember Everything
      description: Every battle is recorded on its own, with the result, damage, kills, map, mode, tank, agent and the loadout you took in, plus everyone else in the match. Browse it all through Overview, Battle list, Trends and Session, broken down by tank, agent, map and mode. Open a profile for any player you have met, with their win rate with and against you. Keep a 1v1 score against every opponent, with your best and worst tanks against them and every encounter listed. Track your platoon mates, the XP of every tank and agent, and your loadouts read straight from your account, even for tanks you have never taken out. Earn up to three Marks of Excellence per tank from your damage per minute over the last 50 battles. Filters leave chosen modes, maps or tank-swap battles out of every page at once.
    - enabled: true
      icon: <i class="fa-solid fa-sliders"></i>
      name: Your Game, Your Interface
      description: Battle HUD hides any part of the HUD, radar, nameplates, kill feed, markers, scoreboard and hangar screens, saved as presets. Sight swaps your crosshair, reload, magazine and overheat gauge for reticle packs from a public catalogue, or ones you draw yourself in Sight Forge. Colors adds a COLORS tab to the game's own Settings, with colour-blind profiles and presets you share as a code. Minimap draws the real map under your radar, following your floor, with class icons on every dot. Team alerts let you ask for cover, answer a call for help and get warned before a teammate rams you off your spot. Tags put your own marks on players, shown on the scoreboard and above their tanks. Friends brings an online list and squad invites into the hangar, and QOL adds platoon auto-ready, platoon marks and a post-battle skip straight to the hangar.
    - enabled: true
      icon: <i class="fa-solid fa-puzzle-piece"></i>
      name: Add-ons
      description: Optional extras that sit idle until you switch them on. Tactics Board plans rounds on the real maps, with timed routes, arrows, areas, notes, every floor of multi-level maps, rosters, a strategy library, a phase-by-phase playback and sharing by file, code or link. Replays keeps the replays the game would delete and plays them with a free camera, gunner view, outlines through walls, shot paths, a tank panel and rewind. HEAT Snap clips a streamer's Twitch broadcast when you destroy them or they destroy you. HEAT Sabotage lets a streamer's viewers spend channel points to switch off parts of the HUD.
    - enabled: true
      icon: <i class="fa-solid fa-layer-group"></i>
      name: Overlays, Builds and More
      description: An in-game overlay with stat tiles, ability gauges, team composition by remaining health and your marks progress, each shown only when it matters, like during a round or while aiming. A stream overlay for OBS that you edit live while you stream. Named builds with a Build Composer that keeps to the energy and slot rules, one-click apply and sharing as a code or a link. Discord Rich Presence, twelve languages, two looks and a built-in updater.

overview:
  enabled: true # Maximum of 4 images.
  description: HEAT Sentinel runs next to WoT HEAT and remembers everything the game forgets. Every battle you play is recorded on its own and turned into your history, your tanks and agents, your loadouts, your platoon, a profile for every player you meet, a running 1v1 score against each of them, and Marks of Excellence for every tank. It also gives you the interface you actually want, from custom sights and your own colours to a real map under the radar, team alerts for teammates without a microphone, and marks above the players you want to keep an eye on. Add-ons bring a Tactics Board for planning rounds on the real maps, a replay library with a free camera, and tools for streamers. There is no account to make. Your battles stay on your PC, Sentinel only reads what you can already see on screen, and every release is built in the open and scanned on VirusTotal.
  layout: grid # none | single | two | heroPlusTwo | grid
  images:
    items:
      - https://raw.githubusercontent.com/OxCone1/HEAT-Sentinel/main/heat-labs/stats-overview.png
      - https://raw.githubusercontent.com/OxCone1/HEAT-Sentinel/main/heat-labs/rivals-1v1.png
      - https://raw.githubusercontent.com/OxCone1/HEAT-Sentinel/main/heat-labs/loadouts.png
      - https://raw.githubusercontent.com/OxCone1/HEAT-Sentinel/main/heat-labs/moe.png

installation:
  enabled: true
  description: There is nothing to calibrate and no baseline to set up. Install it, point it at the game, and queue.
  steps:
    - name: Step #1
      description: Download the installer from the latest release and run it. Windows SmartScreen will warn about an unknown publisher, so click More info, then Run anyway. Every release is built by GitHub Actions and its VirusTotal scan is linked on the release page if you want to check it first.
    - name: Step #2
      description: Open HEAT Sentinel and point it at your game folder in the first-launch setup. If the game was already running, restart it once.
    - name: Step #3
      description: Queue into a battle right away. Battles are recorded on their own while the app is open, and the first time you reach the hangar it reads your tanks, XP, modules, equipment, perks and agents from your account, including tanks you have not played yet. Change a loadout later and it picks that up by itself too.
    - name: Step #4
      description: Make it yours whenever you like. The Game UI tab holds the Battle HUD, sights, colours, minimap, team alerts, tags, friends and QOL options, the Overlay tab lays out what shows on screen and on stream, and the Add-ons tab switches on the Tactics Board, Replays, HEAT Snap and HEAT Sabotage.

troubleshooting:
  enabled: true
  description: Most problems after an update come from an old copy still running in the background. Work through these in order.
  steps:
    - name: Step #1
      description: If the in-app updater fails, download the installer from the Releases page and run it over your install. Pick Add or repair components if offered, otherwise Do not uninstall.
    - name: Step #2
      description: Still not going through? Close both HEAT Sentinel and heat-capture, check in Task Manager that neither is running, then run the installer again.
    - name: Step #3
      description: If the app says it cannot reach the game after a game update, restart the game once.
    - name: Step #4
      description: Nothing helped? Zip the logs from %LOCALAPPDATA%\HEAT Sentinel\logs and send them on the Discord server. If you uninstall to reinstall, do not tick the option to delete application data, or your battle history goes with it.

videoShowcase:
  enabled: false # Maximum of 4 video cards.
  layout: single # single | two | heroPlusTwo | grid
  videos:
    - title: VIDEO TITLE 1
      thumbnail: https://i.ytimg.com/vi/[VIDEO_ID]/maxresdefault.jpg
      url: https://www.youtube-nocookie.com/embed/[VIDEO_ID]
      creator: CREATOR NAME
      type: Tutorial
---
