#Python for linux users

## How to install python3+ version
Here is link that can help you do that:
http://askubuntu.com/questions/244544/how-do-i-install-python-3-3

## How to install pip
Anoher link to help you achieve that:
http://www.pip-installer.org/en/latest/installing.html

## VirtualEnv
You  can install globally VirtualEnv by using the following command:
```
$ sudo pip install virtualenv
```
Next you need to set up local virtual environment with the following command:
```
example:
$ virtualenv -p /usr/bin/python3 yourenv

the structure:
$ virtualenv -p <pathToPython/PythonVersion> <EnvFolderName>
```
And lastly, you start virtualenv with the command below:
```
$ source EnvFolderName/bin/activate
```
After activating your vurtualenv you will see something like this:
```
$ (env)yourpc@something:~/folder/folder/etc/
```
To install package in your
$ pip install <package-name>
```
