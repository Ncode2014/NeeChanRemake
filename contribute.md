# NeeChan Contribute
## How You can Contribute your self to bring this project can alive
**you need using**
- termux 
- vpn singapore to searching & indonesian vpn to tested this ip (mostly you can get it on tcpvpn.com and use openvpn or you can use vpn app like nordvpn,express vpn,etc)
- Host Go
- QuickEdit
# How to installing this tool
```
open termux and type command pkg upgrade -y && pkg install nmap -y && pkg install dnsutils -y && pkg install wget -y
after that you must type command again wget https://github.com/DNSCrypt/dnscrypt-proxy/releases/download/2.0.45/dnscrypt-proxy-android_arm64-2.0.45.zip && unzip dnscrypt-proxy-android_arm64-2.0.45.zip 
after that you have see android-arm64 folder
```
# how to use this tool
```
Nmap: "nmap -p 80 --script dns-brute.nse url.com "
dnsbrute: cd android-arm64 and type ./dnscrypt-proxy resolve url.com
nslookup: nslookup url.com
```
# how to added/fix url if not found or not working
```
you copy my raw version on my github https://raw.githubusercontent.com/Ncode2014/NeeChanRemake/master/base_host 
and you paste on quickedit after that you change the ip and website

template added (if you added new host)
(example)
[*name website]
*ip *website

template fixed (if you want fix)
(example)
[Google.com]
216.58.211.3 google.com

(and you added to)
[Google.com]
216.58.211.8 google.com
and you open https://github.com/Ncode2014/NeeChanRemake/blob/master/base_host & click edit/icon pencil 
in mode edit you paste fix website your self (which mean you copied all on text include your fix)
and paste on editor mode github 
after that on commit changes
type on updated base_host "fixing *name of website" 
on description "fixed *website"
```
