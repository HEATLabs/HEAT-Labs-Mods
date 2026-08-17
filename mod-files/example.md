---
name: MOD NAME
description: MOD DESCRIPTION
download: DOWNLOAD URL
compatible-version: 0.0.0
status: Available # Available | Work in Progress | Beta Testing | Discontinued
category: Gameplay # First category is primary, others are secondary: Gameplay | Interface | Audio | Visual | Model | Performance | Loader | Statistics
type: Open Source # Open Source | Closed Source

license:
  enabled: true
  name: LICENSE NAME
  url: LICENSE URL

support:
  enabled: true
  description: SHORT SECTION DESCRIPTION
  feedback:
    enabled: true
    name: GitHub Issues
    url: https://github.com/USERNAME/REPOSITORY/issues
  support:
    enabled: true
    name: Discord Server
    url: https://discord.gg/INVITE

features:
  enabled: true # Maximum of 4 feature cards. For icons use fontawesome icons only found here https://fontawesome.com/search?ic=free-collection
  cards:
    - enabled: true
      icon: # Use fontawesome icons only found here https://fontawesome.com/search?ic=free-collection
      name: FEATURE NAME 1
      description: FEATURE DESCRIPTION 1
    - enabled: true
      icon: # Use fontawesome icons only found here https://fontawesome.com/search?ic=free-collection
      name: FEATURE NAME 2
      description: FEATURE DESCRIPTION 2
    - enabled: true
      icon: # Use fontawesome icons only found here https://fontawesome.com/search?ic=free-collection
      name: FEATURE NAME 3
      description: FEATURE DESCRIPTION 3
    - enabled: true
      icon: # Use fontawesome icons only found here https://fontawesome.com/search?ic=free-collection
      name: FEATURE NAME 4
      description: FEATURE DESCRIPTION 4

overview:
  enabled: true # Maximum of 4 images.
  description: MOD OVERVIEW DESCRIPTION
  layout: none # none | single | two | heroPlusTwo | grid
  images:
    items:
      - /images/overview-1.png
      - /images/overview-2.png
      - /images/overview-3.png
      - /images/overview-4.png

installation:
  enabled: true
  description: HOW TO INSTALL DESCRIPTION
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