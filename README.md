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

### Known Issues:

I did find an issue on some keyboards brands where the Num Lock or Caps Lock LED won't blink until I first physically press the lock key to turn it on once.  Then running kbdled works.
* Upon boot, report IP address of DHCP supplied address
* Blink SOS if a machine needs attention
