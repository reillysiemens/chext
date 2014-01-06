chext
=====

A simple Bash script for changing file extensions.

Example Usage
-------------

Changing a file called foo.jpg to foo.png.
```
chext foo.jpg png
```

Changing a file called foo.js to foo.ejs and having chext tell you what it's doing.
```
chext -v foo.js ejs
```

Changing all files in a directory with a .jpg extension to a .png extension.
```
chext -a jpg png
```

Recursively changing all index.html files to index.php files.
```
chext -r index.html php
```

Recursively changing all .html files to .php files.
```
chext -ar html php
```

Recursively changing all .txt files to .md files and having chext tell you what it's doing.
```
chext -arv txt md
```

Acknowledgements
----------------

The following were critical to the development of this script:

* [http://stackoverflow.com/a/12036574](http://stackoverflow.com/a/12036574)
* [http://wiki.bash-hackers.org/howto/getopts_tutorial](http://wiki.bash-hackers.org/howto/getopts_tutorial)
* [http://stackoverflow.com/a/1225236](http://stackoverflow.com/a/1225236)
* [http://stackoverflow.com/a/2353307](http://stackoverflow.com/a/2353307)
