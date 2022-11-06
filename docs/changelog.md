---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
# layout: bare
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- hdr-changelog.md v1.0.0.1
Rusty Star Rockets (RSR)
created: 13 May 2022
updated: 05 Nov 2022
CC BY-ND 4.0 by zer0Kerbal -->  
﻿# Changelog  

| modName    | Rusty Star Rockets (RSR)                                          |
| ---------- | ----------------------------------------------------------------- |
| license    | CC BY-ND 4.0                                                      |
| author     | GagaX and zer0Kerbal                                              |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209405-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/RustyStarRockets)       |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/RustyStarRockets)     |
| spacedock  | (https://spacedock.info/mod/207)                                  |
| ckan       | RustyStarRockets                                                  |

## Version 1.8.99.1-prerelease - `<Rust Koleum: 1st coat>` edition

* Released
  * 05 Nov 2022
  * for Kerbal Space Program 1.12.4
  * by zer0Kerbal

### Summary 1.8.99.1

* ten more parts updated
  * science
    * <rsr-science-lab-1.cfg>
    * <rsr-science-lab-2.cfg>
    * <rsr-science-bay-material.cfg>
    * <rsr-science-exp-goo.cfg>
    * <rsr-science-exp-rust.cfg>
  * electrical
    * <rsr-elec-reactor.cfg>
    * <rsr-elec-solar-panel.cfg>
    * <rsr-elec-solar-round.cfg>
    * <rsr-elec-solar-stat.cfg>
  * thermal
    * <rsr-therm-rad.cfg>
* for more details, read the release notes for 1.8.99.0
* just doing more of the same

### Status 1.8.99.0

* Issues
  * closes #66 - Rusty Star Rockets (RSR) 1.8.99.1-prerelease `<Rust Koleum: 1st coat>`
  * closes #67 - 1.8.99.1 Verify Legal Mumbo Jumbo
  * closes #68 - 1.8.99.1 Update Documentation
  * closes #69 - 1.8.99.1 Update Social Media
  * updates #62 - Create Thumbs
  * updates #33 - Part Localization
  * updates #16 - English <us-en.cfg>
  * updates #15 - Localization - Master
  * updates #14 - [DRAG_CUBE]
  * updates #11 - Part Asset Updates

---

## Version 1.8.99.0-adoption - `<Thank you GagaX` edition

* 21 Aug 2022
* Released for Kerbal Space Program 1.12.3

### Summary 1.8.99.0-adoption

* First of several staged updates
* Hard dependency is Rusty Star Shipyards (RSS)
  * provides agent, flags, and other common files
* Only parts that have been updated are included
  * all subsequent releases should have these parts (and more)
  * 15 Command
  * 3 Control
  * 2 CompoundParts
* Updated License: CC BY-ND 4.0

### Adopted by zer0Kerbal

### Update License

* Updated License: CC BY-ND 4.0
  * was: CC BY-NC-ND 4.0
* closes #13 - Update License

### Infrastructure 1.8.99.0

* [RustyStarRockets.version]
  * update
  * remove
    * KSP_VERSION_MAX
* Create
  * Hero.png
* closes #8 - Create Hero.png

### Config 1.8.99.0

* Add localized tags to parts
* Create RustyStarRockets.cfg
  * [RustyStarRockets.cfg] v1.0.0.0
    * adds localized tags to parts
* closes #12 - Create RustyStarRockets.cfg

### Parts

* Fix
  * Sphere
    * soundFx
    * GFx
* Lint
  * too many changes to document
* Add
  * header
  * Add/Update [DRAG_CUBE]
* Rename parts and part file
  * Command
    * KerbalInTheBox --> rsr-KerbalInTheBox
    * RSR_Avion --> rsr-avion
    * RSR_Avion2 --> rsr-avion-2
    * RSR_HQ --> rsr-hq
    * RSR_Inline_Cockpit --> rsr-cockpit-inline
    * RSR_SubCP --> rsr-sub-pod
    * RSRmk2Cockpit --> rsr-cockpit-mk2
    * RSRSkullPod --> rsr-skull-pod
    * RustyCapsuleS2 --> rsr-capsule-250
    * RustyCapsuleS2_2 --> rsr-capsule-250-rtg
    * RustyCapsule --> rsr-capsule-125
    * RustyCapsuleAvion --> rsr-capsule-avion-125
    * Size2AvionCockpit --> rsr-capsule-avion-250
    * sphere --> rsr-sphere-125
  * Compound
    * RSRstrutConnector --> rsr-strut-connector
    * RSRfuelLine --> rsr-fuelLine
  * Control
    * RustyRCS_block --> rsr-rcs-block
    * RustyReactionWheel --> rsr-rw-125
    * RustyReactionWheel2 --> rsr-rw-250
* updates #14 - [DRAG_CUBE]

### ghostparts

* Create
  * [ghostparts.cfg]
  * this patch which will go away
* closes #61 - ghostparts

### Create Thumbs

* Create
  * @thumbs/
  * add thumbnails

* updates #62 - Create Thumbs

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* convert from .tga (470kb) --> png (148kb)
* Rename and relocate
  * models to unique names
    * Command
      * model.mu - rsr-KerbalInTheBox.mu
      * NewModel.mu --> rsr-avion.mu
      * model.mu --> rsr-avion-2.mu
      * model.mu --> rsr-hq.mu
      * NewModel.mu --> rsr-cockpit-inline.mu
      * NewModel.mu --> rsr-sub-pod
      * mk2cockpit.mu --> rsr-cockpit-mk2.mu
      * NewModel.mu --> rsr-sub-pod
      * model.mu --> rsr-capsule-250
      * model.mu --> rsr-capsule-250-rtg.mu
      * model.mu --> rsr-capsule-125.mu
      * model.mu --> rsr-capsule-avion-125.mu
      * NewModel.mu --> rsr-capsule-avion-250.mu
      * sphere.mu --> rsr-sphere.mu
    * Compound
      * model.mu --> rsr-strut-connector.mu
      * model.mu --> rsr-fuelLine.mu
    * Control
      * NewModel.mu --> rsr-rcs-block.mu
      * model.mu --> rsr-rw-125.mu
      * model.mu --> rsr-rw-250.mu
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* updates #11 - Asset Updates

### Convert Sound Assets

* Convert
  * sound_gecko
  * sound_iguana
  * sound_komodo
  * soundSPHERE
    * from `wav` to `ogg`
    * from 9.42mb --> 374kb
* closes #60 - Convert Sound Assets

### Localization 1.8.99.0

* Create
  * Localization directory and contents
  * Create
    * Localization/
      * <en-us.cfg>
      * [readme.md] v2.1.2.0
      * [quickstart.md] v1.0.1.1
  * Agency
  * run localizer
  * Parts to localize
    * [PART.cfg]
  * closes #10 - Create Localization directory and contents
  * updates #15 - Localization - Master
  * updates #16 - English <us-en.cfg>
  * updates #33 - Part Localization

### Archival Releases

* fixed bugs found while creating
  * extra closing brace for PART{}
    * wingSquareDouble2.cfg
  * missing closing brace for PART{}
    * RustyWing.cfg
    * RustyWingD.cfg
    * RustyFuelTankSphere3.cfg
  * extraneous closing brace
    * RSRmk2Cockpit.cfg
  * [description] = split between two lines with hard returns instead of \n\n
    * RadialParachute2.cfg
    * RSR_RadialParachute2.cfg
    * transport.cfg
    * RSR_HH.cfg
    * RSR_radial.cfg
    * DrogueChute.cfg
    * RadialParachute2.cfg
* closes #46 - [Bug]: part.cfg errors

### GitHub Pages 1.8.99.0

* docs/
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Disclaimer.md] v1.0.1.0
  * [HowItWorks.md] v1.1.0.0
  * [PartsCatalog.md] v1.1.4.1
  * [resourceFlow.md] v1.0.1.0
  * [Why.md] v1.1.0.0
* closes #7 - Create GitHub Pages

### Status 1.8.99.0

* Issues
  * closes #3 - Rusty Star Rockets 1.8.99.0-adoption <Thank you GagaX> edition
  * closes #4 - 1.8.99.0 Create Legal Mumbo Jumbo
  * closes #5 - 1.8.99.0 Create Documentation
  * closes #6 - 1.8.99.0 Create Social Media Presence

---

## Version 1.8.0.0-release - `<Archival>`

* 19 Jul 2017
* Released for Kerbal Space Program [KSP 1.3.0]

* No changelog provided

### Status 1.8.0.0

* Issues
  * closes #9 - Archival Releases
  * closes #45 - 1.8.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.7.0.1-release - `<Archival>`

* 12 Mar 2017
* Released for Kerbal Space Program [KSP 1.2.2]

* No changelog provided

### Status 1.7.0.1

* Issues
  * updates #9 - Archival Releases
  * closes #44 - 1.7.0.1-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.7.0.0-release - `<Archival>`

* 05 Mar 2017
* Released for Kerbal Space Program [KSP 1.2.2]

* No changelog provided

### Status 1.7.0.0

* Issues
  * updates #9 - Archival Releases
  * closes #43 - 1.7.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.6.0.0-release - `<Archival>`

* 17 Mar 2016
* Released for Kerbal Space Program [KSP 1.1.0]

* added various lights
* added some new engines
* improved textures
* various tweaks

### Status 1.6.0.0

* Issues
  * updates #9 - Archival Releases
  * closes #42 - 1.6.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.5.0.0-release - `<Archival>`

* 25 Jan 2016
* Released for Kerbal Space Program [KSP 1.0.5]

* improved textures
* various tweaks
* new parts:
  * size 0
    * tanks
    * decoupler
  * large liquid fuel tank
  * turbojet engine
  * inline cockpit
  * hypersonic air intake

### Status 1.5.0.0

* Issues
  * updates #9 - Archival Releases
  * closes #40 - 1.5.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.4.0.0-release - `<Archival>`

* 06 Jan 2016
* Released for Kerbal Space Program [KSP 1.0.5]

* new parts:
  * hitchhiker container
  * size 2 vacuum engine
  * new lab
  * some fuel tanks
  * new submarine style command pod
* improved some textures
* various tweaks

### Status 1.4.0.0

* Issues
  * updates #9 - Archival Releases
  * closes #39 - 1.4.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.3.0.0-release - `<Archival>`

* 21 Dec 2015
* Released for Kerbal Space Program 1.0.5

* Added moar stuff, including antennae, science experiments, mk2 parts...
* improved textures on some parts
* redistributed parts on tech tree, now it makes some sense
* various tweaks
* ...

### Status 1.3.0.0

* Issues
  * updates #9 - Archival Releases
  * closes #38 - 1.3.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.2.0.0-release - `<Archival>`

* 04 Dec 2015
* Released for Kerbal Space Program 1.0.5

* added moar stufff
* ok, added 2 kinds of wing sets (11 wing parts total)
* finished IVA for lab
* new size1 and size2 cockpits
* some structural parts

### Status 1.2.0.0

* Issues
  * updates #9 - Archival Releases
  * closes #37 - 1.2.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.1.1.0-release - `<Archival>`

* 19 Nov 2015
* Released for Kerbal Space Program 1.0.5

* fixed parachute issues
* added spherical fuel tanks

### Status 1.1.1.0

* Issues
  * updates #9 - Archival Releases
  * closes #36 - 1.1.1.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.1.0.0-release - `<Archival>`

* 16 Nov 2015
* Released for Kerbal Space Program 1.0.5

* added moar stuff

### Status 1.1.0.0

* Issues
  * updates #9 - Archival Releases
  * closes #35 - 1.1.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---

## Version 1.0.0.0-release - `<Archival>`

* 03 Nov 2015
* Released for Kerbal Space Program 1.0.5

* initial release by GagaX

### Status 1.0.0.0

* Issues
  * updates #9 - Archival Releases
  * closes #34 - 1.0.0.0-release
* updates #46 - [Bug 🐞]: part.cfg errors

---
