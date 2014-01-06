chext
=====

A simple Bash script for changing file extensions.

Example Usage
-------------

Change a file called foo.jpg to foo.png.
```
chext foo.jpg png
```

Change a file called foo.js to foo.ejs with output in verbose mode.
```
chext -v foo.js ejs
```

Change all files in a directory with a .jpg extension to a .png extension.
```
chext -a jpg png
```

Recurse into all subdirectories and change all index.html files to index.php files.
```
chext -r index.html php
```

Recurse into all subdirectories and change all .html files to .php files.
```
chext -ar html php
```

Recurse into all subdirectories and change all .txt files to .md files with output in verbose mode.
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
