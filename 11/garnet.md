### Pre-installation:

* Make sure you have latest firmware available for your country.
* Gapps package (optional) (from download page, gapps button)
* Recovery (from download page, recovery button)

### First time installation (clean flash):

* Reboot in recovery
* Format data
* Install last firmware your region
* Reboot recovery
* Install rom.zip
* Reboot recovery 
* Install gapps (optional)
* Start system

```
adb sideload crDroid.zip
```
* When asked to sideload gapps, choose 'Yes' to reboot to recovery or 'No' if you don't want gapps and want to reboot to system
* Now if you choosed to install gapps, simply sideload gapps.zip the same way you installed crDroid.zip then reboot to system

### Update installation:
#### Via recovery (recommended way):
* Boot to recovery
* Choose rom.zip
* Reinstall gapps (optional)
* Wipe cache and dalvik in fox recovery

```
adb sideload crDroid.zip
```
* Choose rom.zip (apply update)
* Reinstall gapps (optional)

#### Via OTA:
* Go to Settings -> System -> Updater and download latest build
* Choose install and let it finish
* If having gapps, reboot to recovery and reinstall gapps package again
* Reboot
