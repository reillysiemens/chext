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
chext -ra html php
```

Recursively changing all .txt files to .md files and having chext tell you what it's doing.
```
chext -rav txt md
```

Acknowledgements
----------------

The following were critical to the development of this script:

* [http://wiki.bash-hackers.org/howto/getopts_tutorial](http://wiki.bash-hackers.org/howto/getopts_tutorial)
* [http://stackoverflow.com/questions/12036445/bash-command-line-arguments](http://stackoverflow.com/questions/12036445/bash-command-line-arguments)
* [http://stackoverflow.com/questions/1224766/how-do-i-rename-the-extension-of-a-batch-of-files](http://stackoverflow.com/questions/1224766/how-do-i-rename-the-extension-of-a-batch-of-files)
