SQLite3-Universal-Binaries

Universal (well almost, support from arm-v7+ ) SQLite3 binaries for Android

This module will first check to see if an SQLite3 binary already exists in the common paths (as per my GPay SQLite Fix module), so it doesnt try and install another or overwrite an existing one. 

Again, only armeabi-v7a architecture and above is provided by this module

Specifically supported:

    armeabi-v7a
    arm64-v8a
    x86
    x86_64

This module will put an sqlite3 binary into /system/bin if /system/xbin is not present

Any scripts relying on this sqlite3 binary need to check both paths for sqlite....

Project Stats:   

![GitHub release (latest by date)](https://img.shields.io/github/v/release/stylemessiah/SQLite3-Universal-Binaries?label=Release&style=plastic)
![GitHub Release Date](https://img.shields.io/github/release-date/stylemessiah/SQLite3-Universal-Binaries?label=Release%20Date&style=plastic)
![GitHub Releases](https://img.shields.io/github/downloads/stylemessiah/SQLite3-Universal-Binaries/latest/total?label=Downloads%20%28Latest%20Release%29&style=plastic)
![GitHub All Releases](https://img.shields.io/github/downloads/stylemessiah/SQLite3-Universal-Binaries/total?label=Total%20Downloads%20%28All%20Releases%29&style=plastic)
