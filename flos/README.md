# ForkLineage OS
![image](https://user-images.githubusercontent.com/30686963/129340582-c5edac6e-cbfa-4750-acf9-ea62bf84af5c.png)

# Changelogs
### 29/08/2021
- Add miui camera port (A Lighter verison of ANXcam) Thanks to @neobuddy89
- Import GPS stack from LA.UM.9.1.r1-0700-SMxxx0.0
- Build the GPS/GNSS stack from source
- Switch to AOSP bt stack
- Remove unused colormodes from Display settings (we have KCAL)
- Bring back refresh rate adjustment in DeviceSettings (removed from Settings>Display)
- Cleanup trees and reduce log spam

Note: If KCAL doesnt work, toggle Reading mode in LiveDisplay once and try again

### Check previous changelog [HERE](https://raw.githubusercontent.com/makhk-devices/Changelogs/main/flos/changelog.txt)

# Flashing Instructions
### Clean Flash (From other ROMs)
- Reboot to recovery
- Flash ROM, Gapps and Magisk (Optional)
- Format DATA (!! Backup data before doing this !!)
- Reboot

### Dirty Flash (From previous build of same ROM)
- Reboot to recovery
- Flash ROM, Gapps and Magisk (Optional)
- Wipe Caches
- Reboot
