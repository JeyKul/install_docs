### Pre-installation:

* Make sure you are on latest Pixel firmware installed
* Recovery (from download page, recovery button)
* Gapps Inbuilt
* Optional KernelSU apk (get it on [release page](https://github.com/tiann/KernelSU/releases) from their GitHub - click "show all assets" to see the apk)

### First time installation (clean flash):
* Backup your data to PC, OTG flash drive
* Boot to fastboot and flash recovery

```
fastboot flash vendor_boot vendor_boot.img
```
* Boot to Crdroid recovery
* Format Data
* Now sideload crDroid zip

```
adb sideload crDroid.zip
```
* Reboot to system

### Update installation:
#### Via OTA:
* Go to Settings -> System -> Updater and download latest build
* Choose install and let it finish
* Reboot
