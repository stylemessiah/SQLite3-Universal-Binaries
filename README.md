# SQLite3-Universal-Binaries
Universal (well almost, support from arm-v7+ ) SQLite3 binaries for Android

Again, only armeabi-v7a architecture and above is provided by this module

Specifically supported:

-armeabi-v7a
-arm64-v8a
-x86
-x86_64


This module will put an sqlite3 binary into /system/bin if /system/xbin is not present

Any scripts relying on this sqlite3 binary need to check both paths for sqlite....


