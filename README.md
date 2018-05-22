# CVE-2018-8120
CVE-2018-8120 Windows LPE exploit

Supports both x32 and x64.

Tested on: Win7 x32, Win7 x64, Win2008 x32, Win2008 R2 x32, Win2008 R2 Datacenter x64, Win2008 Enterprise x64.

![image](https://github.com/unamer/CVE-2018-8120/blob/master/screenshot.bmp)

## Usage
```shell
CVE-2018-8120 exploit by @unamer(https://github.com/unamer)
Usage: exp.exe command
Example: exp.exe "net user admin admin /ad"
```
## Caution
* Please exclude shellcode.asm if you wanna compile x32 version.

## Reference
* https://xiaodaozhi.com/exploit/156.html
* https://github.com/bigric3/cve-2018-8120
