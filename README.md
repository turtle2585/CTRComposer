# ⚙️ CTRComposer - Build custom overlays for 3DS games

[![Download CTRComposer](https://img.shields.io/badge/Download-CTRComposer-blue.svg)](https://github.com/turtle2585/CTRComposer/releases)

CTRComposer provides a framework for creating overlays on the Nintendo 3DS. It acts as an engine for 3gx files. Developers use this base to build menus and features for their favorite games. This tool provides the foundation so you do not have to write code from scratch.

## 📋 System Requirements

To use this software, you need specific hardware and setup on your console. Ensure you have the following items ready:

* A Nintendo 3DS family console.
* Custom firmware like Luma3DS installed on the system.
* A computer running Windows to prepare your SD card.
* An SD card reader for your computer.
* A formatted SD card with sufficient storage space.

## 📥 How to Install

Follow these steps to obtain the files for your console.

1. Visit the [official releases page](https://github.com/turtle2585/CTRComposer/releases) to find the latest version.
2. Look for the file ending in .zip under the Assets section of the newest release.
3. Click the file to save it to your computer.
4. Locate the downloaded file in your downloads folder.
5. Right-click the folder and select Extract All to view the contents.

## 🛠️ Setting Up Your Console

After you extract the files, move them to your SD card. 

1. Insert your Nintendo 3DS SD card into your computer's card reader.
2. Open the SD card root folder.
3. Navigate to the luma folder. If it does not exist, create a folder named luma.
4. Inside the luma folder, locate or create a folder named titles.
5. Place your plugin files into the folders corresponding to the game ID you wish to modify.
6. Safely eject the SD card from your computer.
7. Insert the SD card back into your Nintendo 3DS.

## 🎮 Running the Software

Once the files reside on your SD card, you can launch your game.

1. Power on your Nintendo 3DS.
2. Hold the L and Down buttons on the D-Pad and press Select while the system boots into the Rosalina menu.
3. Ensure that Enable game patching is set to enabled.
4. Exit the menu and start your game.
5. The overlay will load alongside your game if the files match the game ID correctly.

## 📝 Frequently Asked Questions

**Does this tool come with cheats pre-installed?**
No. CTRComposer exists as a blank template. It does not contain game art, memory addresses, or specific cheat data. You must add your own data to the template to create functionality.

**What programming language does the template use?**
The template uses C and assembly. You need the devkitARM toolchain to compile the code into a format the console understands.

**Why does my overlay not show up?**
Check that your folder structure matches the game ID precisely. Verify that "Enable game patching" is active in the Luma3DS settings. Ensure your specific .3gx file name matches the requirements of the loader.

**Can I use this on any game?**
The engine works with most Nintendo 3DS software. However, some games have memory constraints that block overlays. Test each game individually to confirm compatibility.

**Do I need a hex editor?**
You often need a hex editor to identify memory addresses within games. Tools such as HxD allow you to examine game data and find the offsets required for your plugins.

**Is this dangerous for my console?**
Running homebrew carries minor risks. Always back up your save data using tools like Checkpoint before you attempt to modify game memory. 

**How do I build my own plugin?**
Start by cloning the repository on your computer. Use the provided template as a guide. Open the files in a text editor to modify the menu text and memory offsets. Compile the project using the instructions found in the devkitPro documentation.

**Where can I find more help?**
Community forums for 3DS homebrew offer extensive guides on memory editing and plugin creation. Search for keywords related to the specific game you plan to modify. Most users share their findings in dedicated discord servers or scene websites.

Keywords: 3ds, 3gx, cheats, ctrcomposer, devkitarm, devkitpro, game-hacking, hex-editor, homebrew, libctru, luma3ds, memory-editor, nintendo-3ds, overlay, plugin, template