Setup Parrot
===========

## Battery Charger

-  No light: Battery not charging
-  Red light (solid): Charging
-  Red light (flashing): Battery cells balancing (leave charging)
-  Green light: Charged


## Firmware update

-  Install [https://play.google.com/store/apps/details?id=com.parrot.freeflight&hl=en](AR.FreeFlight)
-  Connect to drone Wi-Fi network (written on sticker)
  -  Android 7: Must tap `Network has no internet access` notification and tap
      `YES` in modal
-  Open or restart the app
-  Tap `AR.DRONE UPDATE` to update firmware
-  Tap `PILOTING` to control drone in-app
  -  Tap Settings Cog => `FLAT TRIM` to reset trim


## Installation

-  Install node.js (through `n` for Linux/macOS or `nvm` for Windows)
-  Optional: install [https://yarnpkg.com](Yarn)
-  `yarn install` or `npm install`

-  Connect to drone Wi-Fi network (written on sticker)
-  `node repl.js` (DO NOT `npm start` or `yarn start`)


## NOTES

-  Drone batteries get warm