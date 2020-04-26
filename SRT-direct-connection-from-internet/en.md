**SRT: direct connection from Internet**
==
*If you have not public IP or have not ability for port-forwarding then please use other way* – [ProxyAddon](http://help.garaninapps.com/2020/02/12/srt-proxy-addon/)

for accept direct connections from INTERNET (for example from stadium or other country) please check this points:

1. **Your “Studio” has public IP.**
 *We provide dynamic DNS name like* “[demo123.rtmpminiserver.com](http://demo123.rtmpminiserver.com/)” . *It will be auto linked to this IP*.

2. **Router has configuration**: all incoming connections from Internet to port 9001 of router transfer to PC with SRT MiniServer. 
*Without this rule your router doesn’t known how handle **UDP** traffic to 9001 port. **This called “”Port Forwarding” or “”Virtual Servers”.***
