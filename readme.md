# JARVIS ROM
To initialise manifest, make sure that you've added and configured your SSH key/connection to [github.com](https://docs.github.com/en/authentication/connecting-to-github-with-ssh "github.com")
then execute the following commands
```shell
repo init -u git@github.com:JARVIS-ROM/android.git -b t
```
```shell
repo sync --no-tags --no-clone-bundle --optimized-fetch --prune -c
```

It will sync the source, you can start compilatio after that. If you need help, check the reference device tree at [android_device_xiaomi_sweet](https://github.com/JARVIS-ROM/android_device_xiaomi_sweet "android_device_xiaomi_sweet")
