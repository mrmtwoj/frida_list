# Frida Help List 
## Install Frida 
```sh
pip install frida-tools
```
## Hook In PackageName
```sh
frida -U -f [.comPackageName] -l [nameScript.js] --no-pause
```

> Note:
`[.comPackageName]` frida-ps -U or View in apk Code use (jadx)
`[nameScript.js]` this javaScript code
https://github.com/skylot/jadx/releases

## Hook In Process
```sh
frida -U -l [nameScript.js] -p [2305]
```
> Note:
`[.2305]` adb shell > ps
`[nameScript.js]` this javaScript code
