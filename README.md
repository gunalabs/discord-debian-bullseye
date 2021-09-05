# Discord for Debian 11 (Bullseye)
#### Refer this: https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=895037
### Context:
From Debian's Bullseye release, the `libappindicator` package is depreciated and replaced with `libayatana-appindicator`.

But, in current(0.0.15) discord installation package, it asks for `libappindicator1` hence the installation breaks in bullseye.

The file in this repo has the dependency replaced with `libayatana-appindicator1` which installs completely without breaking.

