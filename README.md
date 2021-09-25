# Discord for Debian 11 (Bullseye)
#### Refer this: https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=895037
### Context:
From Debian's Bullseye release, the `libappindicator` package is depreciated and replaced with `libayatana-appindicator`.

But, in discord installation packages (including the latest 0.0.16), it asks for `libappindicator1` hence the installation breaks in bullseye.

The files in this repo have that dependency replaced with `libayatana-appindicator1` after which installation succeeds and the app works fine.
