precompiled-binaries
====================

Several pre-compiled binaries (including ECL) for Android OS are posted here.

### Available binaries:
+ ecl
  - Compiled from ecl-android project at https://github.com/ageneau/ecl-android. 
  - For ARM cpu. PIE not supported. Thus good for ARM based Anroid phones/tablets with Android 4.X and before.
 
### How to use pre-compiled binary files
+ Download this project
+ adb push ecl /data/local/tmp
+ adb shell (Hereafter, you are in your android device)
+ cd /data/local/tmp
+ chmod 755 ecl
+ ecl

Enjoy!
