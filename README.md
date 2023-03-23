# Kali-del-script
This is a quick file deleting script for kali.

```shell
┌──(user㉿kali)-[~/demo]
└─$ del junk.txt
Do you want to delete this file (y/n): y
```


### To use del-script:

1. Install script from this Repo.
2. Open terminal on your linux device.
3. Go into del file using cd.
```shell
┌──(user㉿kali)-[~]
└─$ cd del
```
4. Give del script permission to delete
```shell
┌──(user㉿kali)-[~/del]
└─$ chmod a+x del
```
5. Then create path for del script into using this command. 
```shell
┌──(user㉿kali)-[~/del]
└─$ export PATH="/home/user/del:$PATH"
```
6. Lastly move del script into sbin using following command.
```shell
┌──(user㉿kali)-[~/del]
└─$ sudo mv del /usr/local/sbin
[sudo] password for user:
```
7. Now you can use del script.



### :fire: Features

- _`Deleting files with only two steps.`_
- _`Easy to use.`_
- _`Customisable.`_

### Prerequisites:

```
You must have Kali Linux or any other Debian based Linux installed.
```

### Q&A's
- why am i keep getting "zsh" error
+ you have to give permission to delete files with "chmod a+x"


### <a href="https://github.com/BAYTEK1N">BAYTEK1N</a>
