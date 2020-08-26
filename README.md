# samsung-safe-debloat-adb
My personal list of disabled apps on my Samsung Galaxy S20+ Exynos.

# Steps:

* [Install adb](https://forum.xda-developers.com/showthread.php?t=2317790)

* [Allow debug usb](https://developer.android.com/studio/debug/dev-options)

* Enter your android shell from you computer's command line:
  ```
  > adb shell
  ```
 
* Copy and paste the "disabled apps.txt" content to disable them all
 
# Utility adb commands:
 
List all disabled apps:
```
pm list packages -d
```
 
List a specific app: (facebook as example)
```
pm list package | grep 'facebook'
```
 
Re-enable apps: (facebook as example)
```
pm enable com.facebook.appmanager
```
