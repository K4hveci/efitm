# efitm
 A tool for fast and easy Man In The Middle attacks with ARP poisoning

 This tool just does arp poisoning, to sniff/listen the packets you need a sniff tool.

 This tool has a reset system, when you stop the poisoning tool sends a normal ARP packet to reset poisoning.


 # How to Install and use
 Clone
 ```
 git clone https://github.com/K4hveci/efitm
 ```
 Move to bin
 ```
 mv efitm /bin
 ```
 To use:
 ```
 efitm -t <target ip> -r <router ip>
 ```
