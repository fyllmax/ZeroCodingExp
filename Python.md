#Python

## How to install python3+ for linux users, here is link that can help you do that: http://askubuntu.com/questions/244544/how-do-i-install-python-3-3

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
$ virtualenv -p <python folder/pythonversion> <EnvFolderName>
```
And lastly, you start virtualenv with the command below:
```
$ source yourenv/bin/activate
```
After activating your vurtualenv you will see something like this:
```
$ (env)yourpc@somethingelse:~/folder/folder/etc/
```
To install package in your
$ pip install <package-name>
```
