# Magisk

A Magisk module that adds the equivalent of "Wireless(WiFi) Debugging Option" to Stock ROM's running Magisk.

With this module one can have WiFi ADB enabled at all times irresepctive of whether an app is using it(ADB) or not.

A default PORT for wireless debugging is 5555. But with this module you can configure the PORT to one that only YOU know.
This way your Wireless debugging(WiFi ADB) will be secure and private(SAFE)

## Usage

Enable this module in magisk.

## How Does It Work

By setting properties in Android to enable WiFi ADB:

``` shell
su
setprop service.adb.tcp.port 5555
stop adbd
start adbd
```
