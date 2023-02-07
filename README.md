# TheParasiteProject

* Some minimal changes applied personal AOSP project,<br/>
  which based on PixelExperience,</br>
  that add Google Play System Update, Carrier Settings, and features that of personal taste :P<br/>
  by `Parasitizing` on other AOSP projects.

## Build Process

### Sync ###

* First, please following `Sync` instruction in [fork of PixelExperience's manifest](https://github.com/TheParasiteProject/manifest)<br>
  After that, following below instruction.

```bash

# Clone
$ git clone https://github.com/TheParasiteProject/local_manifests .repo/local_manifests

# Sync
$ repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

## Credits
- [Acme UI](https://github.com/AcmeUI)
- [AOSPA](https://github.com/AOSPA)
- [crDroid Android](https://github.com/crdroidandroid)
- [DerpFest AOSP](https://github.com/DerpFest-AOSP)
- [Descendant](https://github.com/Descendant-XI)
- [Evolution-X](https://github.com/Evolution-X)
- [Flamingo-OS](https://github.com/Flamingo-OS)
- [hentaiOS](https://github.com/hentaiOS)
- [LineageOS](https://github.com/LineageOS)
- [PixelExperience](https://github.com/PixelExperience)
- [ProtonAOSP](https://github.com/protonAOSP)
- [Project Kaleidoscope](https://github.com/Project-Kaleidoscope)
- [StatiX](https://github.com/StatiXOS)
- [Yet another AOSP project](https://github.com/yaap)

<br/>
And many other great projects!
