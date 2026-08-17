---
name: FUSE
description: The first external modding platform for WoT:HEAT. Runs outside the game, installs reviewed plugins in one click, and gives developers a documented TypeScript API for building open-ended mods.
download: https://github.com/AET9RNAL/HEAT-FUSE/releases
compatible-version: 1.1.2
status: Available # Available | Work in Progress | Beta Testing | Discontinued | Prototype | Unknown
category: Loader, Interface, Statistics # First category is primary, others are secondary: Gameplay | Interface | Audio | Visual | Model | Performance | Loader | Statistics
type: Open Source # Open Source | Closed Source

license:
  enabled: true
  name: GNU General Public License v3 (with additional terms)
  url: https://github.com/AET9RNAL/HEAT-FUSE/blob/main/LICENSE

support:
  enabled: true
  description: Found a bug or want to request a feature? Open an issue on GitHub. For setup help, plugin development questions, and release announcements, contact me on Discord.
  feedback:
    enabled: true
    name: GitHub Issues
    url: https://github.com/AET9RNAL/HEAT-FUSE/issues
  support:
    enabled: true
    name: Discord
    url: https://discord.com/users/678198830767931431

features:
  enabled: true # Maximum of 4 feature cards. For icons use fontawesome icons only found here https://fontawesome.com/search?ic=free-collection
  cards:
    - enabled: true
      icon: <i class="fa-solid fa-shield-halved"></i>
      name: Non-Invasive Philosophy
      description: FUSE runs as a separate process. It does not modify game files, and all changes performed by FUSE are runtime only - as long as the plugin or FUSE is enabled. Overlays are drawn on their own layer above the window. Plugins can only work with information already available in game's frontend, and every plugin published to the marketplace is reviewed against FUSE's public policies before it goes live.
    - enabled: true
      icon: <i class="fa-solid fa-gear"></i>
      name: Set It Up Once
      description: Drag overlays anywhere, resize them, adjust transparency and rotation, and snap them against each other with smart guides and a grid. Layouts are saved per plugin and restored every session, including separate positions for third person and first person. The same stage feeds straight into OBS as a browser source, so what you arrange once is what your viewers see if you're a streamer or record content for the game.
    - enabled: true
      icon: <i class="fa-solid fa-code"></i>
      name: From Idea to Plugin in an Evening
      description: FUSE provides documented API, global hotkeys, persistent settings, the overlay lifecycle, animation through Motion-Vue or self-contained RIVE overlays, so a working plugin is just a bit of TypeScript. Full API surface and existing plugin code can be found in the repository.
    - enabled: true
      icon: <i class="fa-solid fa-share-nodes"></i>
      name: Built to Be Shared
      description: Your plugin gets a marketplace page with markdown, custom styling, screenshots, declared dependencies, and proper versioning, and players install and update it without ever leaving FUSE.

overview:
  enabled: true # Maximum of 4 images.
  description: WoT HEAT gives you the interface it ships with and no way to extend it. FUSE is the first modding platform for the game - one launcher where you install plugins from a reviewed marketplace, toggle them on and off, and tune them to your liking. Overlays put extra information on screen while you play or restyle native UI elements like energy, cooldowns, match stats, or whatever else the plugins you choose decide to show. Positioning takes one pass, and hotkeys let you move between three states - calibrating an overlay, locking it so your clicks pass through, and interactive mode, where overlays stay put but respond to your mouse so you can use the controls a plugin author exposed. Underneath, FUSE is a full modding runtime with a documented API, so building your own plugin and shipping it to everyone else takes a bit of TypeScript.
  layout: none # none | single | two | heroPlusTwo | grid
  images:
    items:
      - /images/overview-1.png
      - /images/overview-2.png
      - /images/overview-3.png
      - /images/overview-4.png

installation:
  enabled: true
  description: Follow the steps below to install and get started with FUSE.
  steps:
    - name: Step #1
      description: Install FUSE from the latest release, then open the launcher.
    - name: Step #2
      description: In Settings, select your game instance and point FUSE at the installation directory. The path must resolve to the game's root folder (for example, C:\YourPath\HEAT). Then turn on the Master Switch.
    - name: Step #3
      description: Create an account to unlock the marketplace. Each plugin page lists what it does, what it draws on screen, and what dependencies it needs to function.
    - name: Step #4
      description: Start HEAT, then press Launch in FUSE. Every plugin that draws on screen opens in calibration so you can position it, then Ctrl+L (by default) locks it in place and your clicks pass through to the game. Some plugins ask for two positions one for third person, one for first - and take one Ctrl+L each. Press Ctrl+I (by default) at any time after calibration for interactive mode, where overlays stay where you put them but respond to your mouse, and press it again to lock them back down. Both hotkeys are rebindable.

videoShowcase:
  enabled: true # Maximum of 4 video cards.
  layout: single # single | two | heroPlusTwo | grid
  videos:
    - title: HEAT FUSE MOD GUIDE
      thumbnail: https://i.ytimg.com/vi/T4n21eZ9uuY/maxresdefault.jpg
      url: https://www.youtube-nocookie.com/embed/T4n21eZ9uuY
      creator: TheCommandersHatch
      type: Tutorial
---