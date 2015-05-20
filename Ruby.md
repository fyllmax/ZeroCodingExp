#Ruby for linux users

## How to install ruby with ruby version manager/rvm/
What is RVM for more info check here: https://rvm.io/

```
$ gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3

```
and then
```
$ \curl -sSL https://get.rvm.io | bash -s stable
```
this will only isntall RVM, if you want to all in one installation append  ```--rails or  --ruby or  --ruby=1.9.3```

## RVM basic commands
See all ruby versions:
```
$ rvm list
```

Switch ruby versions:
```
$ rvm use 2.1.1
$ ruby -v
ruby 2.1.1p76 (2014-02-24 revision 45161) [x86_64-darwin12.0] 

$ which ruby
/Users/rys/.rvm/rubies/ruby-2.1.1/bin/ruby
```

Use ruby system version:
```
$ rvm use system
```

or switch to other default ruby version:
```
$ rvm --default use 2.1.1\etc.\
```

## Errors
RVM is not a function, selecting rubies with 'rvm use ...' will not work. NOW WHAT?

You need to run the follow
```
$ source ~/.rvm/scripts/rvm
```
then run this
```
$ type rvm | head -n 1
```
and if you get ```rvm is a function```, AND the problem is solved!

## Install RubyGems
The RubyGems software allows you to easily download, install, and use ruby software packages on your system.

```
$ sudo apt-get install rubygems
```

## Jekyll
To install Jekyll, the best way to do it is:
```
$ gem install jekyll
```
