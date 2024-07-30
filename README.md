I changed it to like check the image periodically and update it if it changes like how the normal image source does. So like if you wanted to change the reaction image source from a picture of a character talking to a picture of a character ANGRILY talking on the fly with a batch script that copies "ANGRY.png" to "current_talking_face.png" when you press a button on your stream deck or something, the image reaction source will update when the image changes.

# OBS Image Reaction Plugin
Image that reacts to sound source.

## Install Plugin
Idk how to make an installer so you'll have to manually move the plugin data into your obs installation directory (usually "C:\Program Files\obs-studio")
1. Go to the releases page for this repo.
2. Download the .zip
3. Extract and move to your obs installation directory
![moving the files to the obs folder](https://github.com/asgrk/obs-image-reaction-with-auto-refresh/blob/main/move%20to%20obs%20folder.gif)

## Build Plugin Locally
---
To build the plugin follow these steps:
1. In a terminal, run the command:
2. After that has completed, move into the repo directory:
3. Build the plugin: there are three build options (Linux, Mac OS and Windows). Depending on the platform you are on run the build script for your platform e.g. for MacOS:
   ```shell
   .github/scripts/build-macos.zsh
   ```
4. Look in the release folder for the package. For Mac OS this will be `./release/MacOS/`.
5. Copy your package to the obs plugins folder on your computer.
   
