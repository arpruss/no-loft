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

Some users got modding warning popups. USE AT YOUR OWN RISK and don't blame me if you get
banned or something. And consult a lawyer if you want to know about compatibility between
this an the Meta EULA.