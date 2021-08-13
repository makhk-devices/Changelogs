# Post Image
![image](https://user-images.githubusercontent.com/30686963/129340582-c5edac6e-cbfa-4750-acf9-ea62bf84af5c.png)

# Changelogs
### 13/08/2021
- Fix devicesettings icon color
- set the scale to 0.8 when the camera isn't in use
- set the status bar height to 100px
- Import CarrierConfig with LA.UM.9.1.r1-09200-SMxxx0.0
- Use dex2oat64
- Add Via Browser prebuilt  *replace DuckDuckGo
- Update build fingerprint from Redfin - RQ3A.210805.001.A1
- sepolicy: allow hal_audio_default to interact with audio props
- Use ROM's refresh rate handling and set 120Hz as default (Dropped from Devicesettings)
- Improve dt2w handling
- sepolicy: address some perf denials
- sepolicy: Add interface entry for Legacy NFC HAL
- sepolicy: Allow vendor_init to write sched nodes
- Import batterysecret service from stock
- sepolicy: Allow system_server to read fastcharge node
- system.prop: add dex2oat & time props
- Show a ring on the camera cutout when its in use
- sepolicy: Address some hal_audio denials
- sepolicy: Address suspend service denial
- Misc Improvements

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
