#taggerXML#
Modernized version of Eric Brill's Part Of Speech tagger.
The original code is converted to C++.
The program can handle XML input.
This program can only tag. For training the tagger with a tagged corpus of your
own choice you can use Eric Brill's original software.

You can find a copy of Eric Brill's tagger here:

    [cst.dk/download/tagger/RBT1_14.tar.Z](http://cst.dk/download/tagger/RBT1_14.tar.Z)

This file contains linguistic resources for tagging English text as well.

**Installation**

* Linux/Mac/ Windows(one way is chocolatey and make+mingw)?:
    1. Run 'git clone --recursive https://github.com/Watchfulio/taggerXML'
    2. Change directory to the 'taggerXML/src' directory.
    3. Run 'make' or 'make taggerXML'. To get rid of object files, run
    4. 'make clean'.

**Running**

For running the taggerXML, see Eric Brill's original documentation and https://github.com/kuhumcst/taggerXML/blob/master/doc/improvements.md
