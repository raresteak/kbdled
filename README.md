# Readme
Visually send morse code from the caps lock key LED.  

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
Change the morse code speed by changing the TIME variable at the top of the script.
