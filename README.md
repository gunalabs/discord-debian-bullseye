# Discord for Debian 11 (Bullseye)
# UPDATE:
## Discord, in its release `0.0.18` has officially updated the dependencies that could support both `libappindicator1` and `libayatana-appindicator1` by adding both as recommendations (precedence to the former though) in the control file as:
`Recommends: libappindicator1 | libayatana-appindicator1`

It is good seeing it finally fixed in the official release after four+ such Debian 11 incompatible releases of the app. 

<details><summary>Old details</summary>
  
#### Refer this: https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=895037
### Context:
From Debian's Bullseye release, the `libappindicator` package is depreciated and replaced with `libayatana-appindicator`.

But, in discord installation packages (including the latest 0.0.17), it asks for `libappindicator1` hence the installation breaks in bullseye.

The files in this repo have that dependency replaced with `libayatana-appindicator1` after which installation succeeds and the app works fine.
</details>
