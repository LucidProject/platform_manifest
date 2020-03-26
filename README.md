<p align="center">
  <img src="https://raw.githubusercontent.com/markakash/lucid_stuff/master/IMG_20200331_150458_241.png" />
</p>
A project for fun :)

Credits
-------
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**Dirty Unicorns**](https://github.com/DirtyUnicorns)

# Lucid
Simplicity is the ultimate sophistication!

### Requirements
- Around 100G disk space
- 50G or more usable internet
- A computer with at least 8G RAM running Linux or MacOS
- A brain

### Instructions
1. Make sure you have a build environment setup.
2. Run the following commands to sync Lucid source

	```bash
        mkdir Lucid && cd Lucid
        repo init -u https://github.com/Lucid-Beta/platform_manifest -b queen-cake
        repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
	```

3. Once the source is downloaded prepare your trees and build.
4. Until the build is done eat some cakes.

### Reporting compilation issues
- For common porting related errors, visit [**Android Building Help**](https://t.me/AndroidBuildingHelp)

### Adding Support
- For adding your device to the list of supported devices, please message [**Markakash**](https://t.me/markakash) with your device tree and previous experience in building roms.

### Happy Building :)
