### Corvus Revived Project ###

# Initialize Local Repository #
```bash
repo init -u https://github.com/CorvusAOSP-Revived/android_manifest.git -b 11
```

# Or Initialize Shallow Clone #
```bash
repo init --depth=1 -u https://github.com/CorvusAOSP-Revived/android_manifest.git -b 11
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

# Building Environment #
```bash   
# Set up environment
. build/envsetup.sh

# Choose a target
lunch corvus_device-userdebug

# Build the ROM
make corvus
```

# Telegram Support
[![Telegram](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/Telegram_button.png)](https://t.me/corvus_revived)

 Credits:
 =======

 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**HavocOS**](https://github.com/Havoc-OS)
 * [**LineageOS**](https://github.com/LineageOS/)
 * [**HavocOS Revived**](https://github.com/Havoc-OS-Revived/)
