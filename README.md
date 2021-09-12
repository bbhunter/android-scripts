# Android scripts
Some extremely simple scripts that I use during bug bounty hunting in Android Apps.
- All this scripts need an ADB connection to work properly.
- For now, you need to have *only one* connection on ADB.

---
>### ☕ [nidecom.sh](https://github.com/i5nipe/android-scripts/blob/master/nidecom.sh)
Decompile all *.apk files from the current folder with apktool.

---
>### ☕ [nidoap.sh](https://github.com/i5nipe/android-scripts/blob/master/nidoap.sh)
Read a list of package names and open the page of Play Store to download the App.
- Example of use: `./nidoap.sh packages.txt` or `./nidoap.sh com.instagram.android`

---
>### ☕ [nipak.sh](https://github.com/i5nipe/android-scripts/blob/master/nipak.sh)
Extract APK file from App downloaded from Google Play Store.
- Example of use: `./nipak.sh com.instagram.android`

---
>### ☕ [niadump.sh](https://github.com/i5nipe/android-scripts/blob/master/niadump.sh)
Automation for *PASSIVE* analysis of Android communication.
- Need tcpdump binary in "/data/local/tmp/tcpdump"
