---
name: HEAT Sentinel
description: The all-in-one mod for battle tracking and interface tweaking for WoT:HEAT. Records every battle by itself, keeps a running score against every player who has ever killed you, and rebuilds the game's interface with your own colours, overlays and player marks.
download: https://github.com/OxCone1/HEAT-Sentinel/releases
compatible-version: 1.1.2
status: Available # Available | Work in Progress | Beta Testing | Discontinued | Prototype | Unknown
category: Statistics, Interface, Visual # First category is primary, others are secondary: Gameplay | Interface | Audio | Visual | Model | Performance | Loader | Statistics
type: Closed Source # Open Source | Closed Source

license:
  enabled: true
  name: Proprietary (free for personal use)
  url: https://github.com/OxCone1/HEAT-Sentinel/blob/main/COPYRIGHT.md

support:
  enabled: true
  description: Found a bug or want to ask for a feature? Open an issue on GitHub. For setup help and release news, join the Discord server.
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
      name: Every Battle You Play, Kept
      description: The results screen shows you a pile of numbers and then it is gone. Sentinel writes all of it down instead. You do not press anything to start it. Play, and afterwards you have your whole history to look through, sorted by tank, map, mode and agent, the modules you had on at the time, how your platoon does together, and how the current evening is going compared to your all time numbers. Swap tanks in the middle of a battle and the damage is counted for each tank separately, not dumped on whichever one you finished in.
    - enabled: true
      icon: <i class="fa-solid fa-crosshairs"></i>
      name: I've seen you before
      description: Everyone you have ever fought gets a running score. How many times you got them, how many times they got you, which of your tanks does well against them and which of theirs ruins your day, plus every single encounter listed out. You can also put a label on a player, and that label shows up right next to their name in the game, on the scoreboard and on the after battle screens. The one who farmed you last week is marked before the battle even starts.
    - enabled: true
      icon: <i class="fa-solid fa-palette"></i>
      name: Make the Game Look How You Want
      description: Open the game's settings and there is a new COLORS tab sitting next to GAMEPLAY, VIDEO, AUDIO, MOUSE and CONTROLS, in the game itself, not in some window off to the side. Change the colours of enemy and ally markers, capture points, the HUD and the scoreboard, save what you like as a preset, and pick a colour blind friendly set if you need one. Next to that there is a list of interface bits you can simply switch off, so the clutter you never looked at stops taking up your screen. Your friends list is in there too, as its own tab in the hangar, showing who is online and letting you invite them to a squad without alt tabbing.
    - enabled: true
      icon: <i class="fa-solid fa-layer-group"></i>
      name: One Overlay for You, One for Your Viewers
      description: The first one sits on top of the game and is yours. Put your win rate, K/D, damage, streaks, ability timers and a small view of both teams wherever you want them, and tell any of it to only show up when it matters, like during a round or while you are aiming. The second one is for OBS and is built the same way, with its own editor. Move something around while you are live and the stream picks it up straight away.

overview:
  enabled: true # Maximum of 4 images.
  description: HEAT Sentinel sits quietly next to WoT HEAT and remembers everything the game does not. It writes down every battle on its own, builds your history, your loadouts, how you do with the people you platoon with, and a personal score against every player you have ever run into. Then it gives you the useful parts back while you play, either on top of the game or on your stream. It also lets you have the interface you actually want. Recolour the markers, the HUD and the scoreboard from inside the game's own settings, hide the elements you never look at, mark players you want to keep an eye on, and pull your friends list into the hangar. There is no account to make and nothing is sent anywhere. Your battles live in a file on your machine, and every release is built and virus scanned in the open so you do not have to take anyone's word for it.
  layout: none # none | single | two | heroPlusTwo | grid
  images:
    items:
      - /images/overview-1.png
      - /images/overview-2.png
      - /images/overview-3.png
      - /images/overview-4.png

installation:
  enabled: true
  description: Getting started takes about five minutes, and most of that is showing the app what you play.
  steps:
    - name: Step #1
      description: Download the installer from the latest release and run it. Windows may put up a warning about an unknown publisher. The virus scan reports for the build are linked on the project page if you want to check for yourself first.
    - name: Step #2
      description: Open HEAT Sentinel and go through the short setup on first launch. After that it stays out of the way and works whenever it is open, with nothing to switch on or off.
    - name: Step #3
      description: Give it a starting point before your first battle. For each tank you play, open its progression tab and scroll to where you are now, then open its modules tab and stay there for a second or two. Whatever it sees there is what gets saved with your future battles in that tank. Do the same for your agents. Change your modules later and you only need to look at that tab again.
    - name: Step #4
      description: Go play. Battles save themselves as they finish. When you feel like tweaking things, the Overlay tab is where you lay out what shows on screen, and the Game UI tab is where the colours, the interface tweaker, player labels and your friends list live.

troubleshooting:
  enabled: false
  description: COMMON TROUBLESHOOTING STEPS
  steps:
    - name: Step #1
      description: STEP 1 DESCRIPTION
    - name: Step #2
      description: STEP 2 DESCRIPTION
    - name: Step #3
      description: STEP 3 DESCRIPTION
    - name: Step #4
      description: STEP 4 DESCRIPTION

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
