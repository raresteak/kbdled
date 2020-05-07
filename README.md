# Readme
Visually send Morse Code from a keyboard LED (Num Lock, Caps Lock, or Scroll Lock.  

I was inspired by a paper written by Mordechai Guri, Boris Zadov, Dima Bykhovsky, Yuval Elovici titled "CTRL-ALT-LED: Leaking Data from Air-Gapped Computers via Keyboard LEDs" https://arxiv.org/pdf/1907.05851.pdf

### Requires:

xdotool package

Debian/Ubuntu:
```
sudo apt install xdotool
```  
Redhat/Centos:
```
sudo yum install xdotool
```
### Usage:
```
./kbdled "the quick brown fox jumps over the lazy dog"
```
Change the Morse Code speed by changing the TIME variable at the top of the script.

Change led to blink by changing the KEY variable at the top of the script.

### Scenarios:
* Irritate your co-workers
* As part of other scripting, report high temp conditions of machines in a lab. 
* Upon boot, report IP address of DHCP supplied address
* Blink SOS if a machine needs attention
