# Frida Help List 
## Install Frida 
```sh
pip install frida-tools
```
## ❤
https://frida.re/docs/home/

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

## Hook AES And Convert VI , SECURITY CODE (use python ,  string.hex())
```python
python > b'dwc512w1d321wf74w5c4vwdcdxw32fd32w4f'.hex();
```
