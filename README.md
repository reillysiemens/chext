chext
=====

A simple Bash script for changing file extensions.

Example Usage
-------------

Changing all files in a directory with a .jpg extension to a .png extension.
```
user@hostname:~$ ls
bar.jpg foo.jpg
user@hostname:~$ chext jpg png
chext: bar.jpg --> bar.png
chext: foo.jpg --> foo.png
user@hostname:~$ ls
bar.png foo.pjg
user@hostname:~$
```
