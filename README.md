# El Chibre Firmware

This repo is the official firmware repo for El Chibre. It hosts qmk, qmk-vial, zmk aswell as zmk-studio firmware for the El Chibre keyboard.
You can find more info on this keyboard on the [Notion page](https://kbbd.notion.site/El-Chibre-1705a54918cf80c3ae1ae49d5c34f5cb)
Ask questions and join the Discussion over at the [40%s Discord server](https://kbbd.notion.site/El-Chibre-1705a54918cf80c3ae1ae49d5c34f5cb)

## El Chibre QMK
This folder contains everything needed to customize and buid QMK firmware for El Chibre.
You can also just upload the precompiled qmk-vial firmware file directly.

### Customizing QMK
Here's how to customize the QMK keymap to your own preferences:
1. copy the qmk folder inside your local qmk folder
2. Edit your keymap according to the [qmk documentation](https://docs.qmk.fm/)
3. In a qmk environment use ```qmk compile -kb elchibre -km <keymap>``` to compile the qmk firmware (replace ```<keymap>``` with whatever you named your keymap)
4. Flash the compiled .uf2 file found in the qmk root folder to your microchip.

## El Chibre ZMK
This folder contains everything needed to customize and build ZMK firmware for El Chibre.
You can also just upload the precompiled zmk-studio firmware file directly.

### Customizing ZMK
Here's how to customize the ZMK keymap to your own preferences:

1. Fork this repository:
Click the fork button at the top right of this page to copy it into your own GitHub account.
2. Clone your fork locally
3. Edit your keymap according to the [zmk documentation](https://zmk.dev/docs)
4. Commit your changes and push them into your own fork
5. Go to GitHub Actions and download the firmware.zip found under Artefacts
6. Flash the .uf2 file found inside the firmware.zip folder to your microchip
