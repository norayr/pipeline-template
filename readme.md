
In this task you have to write a commandline program which takes strings from the standard input, processes them, and writes to the standard output.

you need to complete one of the following:

* the program takes characters from the stdin, makes all characters in ASCII range lowercase, outputs to the standard output. the name of the output executable should be 'lowercase'.

* program that tokenizes words it gets from the stdin. should output only words, one per line, without punctuation marks. the name of the output executable should be 'makewords'.

* program that transforms ARMSCII-8 text given to stdin to UTF-8 Unicode encoding, writes result to standard output. the output executable should be 'armscii2utf'.

When you complete it, and see/decode what is actually written, try to decode what is written at https://web.archive.org/web/20010118220400/http://www.freenet.am/armnls/fonts.htm

Save it to file, obviously, and then cat it via a pipe to your armscii to unicode converter.

We will compile the program by changing in to the directory, and running 'make'. We will test the program by running one of the makefile sections:

```
make test_makewords
make test_lowercase
make test_armscii2utf
```
Make sure you've edited the makefile in a way we'll be able to compile and test your program.

Useful links:

On ARMSCII
https://en.wikipedia.org/wiki/ArmSCII

https://web.archive.org/web/20000824121519/http://www.freenet.am/armscii/

https://web.archive.org/web/20010118220400/http://www.freenet.am/armnls/fonts.htm

on Makefiles

https://en.wikipedia.org/wiki/Makefile

https://en.wikipedia.org/wiki/Make_(software)

https://www.codeproject.com/Articles/31488/Makefiles-in-Linux-An-Overview

http://www.sis.pitt.edu/mbsclass/tutorial/advanced/makefile/whatis.htm


