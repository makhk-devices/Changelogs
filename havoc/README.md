# Havoc OS - Minkan (Unofficial) for Redmi Note 10 Pro (sweet/sweetin)
## by @makhk
![image](https://user-images.githubusercontent.com/30686963/130345380-650d6212-67e7-42d4-83b1-2d848274e8ff.png)

# Changelogs
### 22/08/2021
- Initial build
- Add miui camera port (A Lighter verison of ANXcam) Thanks to @neobuddy89
- import GPS stack from LA.UM.9.1.r1-0700-SMxxx0.0
- build the GPS/GNSS stack from source 
- Fix devicesettings icon color
- Import CarrierConfig with LA.UM.9.1.r1-09200-SMxxx0.0
- Use dex2oat64
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
