precompiled-binaries
====================

Several pre-compiled ECL (Embeddable Common Lisp) binaries for Android OS are posted here for your conveniences. There are lot of questions such as 'Can I use Common Lisp on Android?' or 'Where to obtain free Common Lisp on Android?'. I hope anyone can start from here, rather than compiling from sources.

### Available binaries:
+ ecl
  - Compiled from ecl-android project at https://github.com/ageneau/ecl-android. 
  - For ARM cpu. PIE not supported. Thus good for ARM based Anroid phones/tablets with Android 4.X and before.
+ ecl-pie
  - Compiled from ecl-android project at https://github.com/ageneau/ecl-android.
  - For ARM cpu. PIE enabled. Thus good for ARM based Android phones/tablets with Android 5.0 Lolipop and later.
 
### How to use pre-compiled binary files
+ Download this project using the 'Download ZIP' button in the right column of this page and expand it.
+ adb push ecl /data/local/tmp
+ adb shell (Hereafter, you are in your android device)
+ cd /data/local/tmp
+ chmod 755 ecl
+ ./ecl

### Licensing
You should follow the licensing terms of ecl-android project and ECL itself when you disribute any work that contains binaries available here.

Enjoy!
