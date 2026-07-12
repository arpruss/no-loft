# no-loft
Keep Horizon OS from reinstalling Loft. Use at your own risk. One user got an anti-mod
warning dialog.

This works for me:
```
adb uninstall com.meta.shell.env.footprint.haven2025
adb install app/haven/release/MuteHome-haven-release.apk
```

But if this isn't enough, you might do this, but this is what triggered the anti-mod
warning:
```
adb uninstall com.meta.shell.env.vista.calming
adb install app/calming/release/MuteHome-calming-release.apk
```
