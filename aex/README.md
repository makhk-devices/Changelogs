# AOSP Extended for Redmi Note 10 Pro (sweet/sweetin)
![image](https://user-images.githubusercontent.com/30686963/129477746-a2cd3481-3e00-4fa9-8603-d53234c29926.png)

# Changelogs
### 22/09/2021
- Add miui camera port (A Lighter verison of ANXcam)
- Update build fp to Redfin - Sepetember 2021
- Import GPS stack from LA.UM.9.1.r1-0700-SMxxx0.0
- Build the GPS/GNSS stack from source
- Switch to AOSP bt stack
- Fix color modes from Display settings
- Fix display color saturation
- Lower screen backlight brightness
- Redesign refresh rate option in DeviceSettings (removed from Settings>Display)
- Import the AOSP fingerprint HAL 2.1
- Import stock power and lights vintf fragments
- Update s5kgw3 camera configs from MIUI v12.5.8.0 RKFINXM
- Drop unnecessary libs
- Some optimizations in kernel (check my git for changes)
- Add back KCAL in devicesettings
- Fix charging stats on lockscreen
- Cleanup trees and reduce log spam

### Source Changelog
- https://blog.aospextended.com/AospExtended-v8.6/

# Flashing Instructions
### Clean Flash (From other ROMs)
- Reboot to recovery
- Flash ROM, Gapps and Magisk (Optional)
- Format DATA (!! Backup data before doing this !!)
- Reboot

### Dirty Flash (From previous build of same ROM)
- Reboot to recovery
- Flash ROM and Magisk (Optional)
- Wipe Caches
- Reboot
