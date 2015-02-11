# libsass-python
----
[![Build Status](https://travis-ci.org/BowdoinOrient/libsass-python.svg?branch=python)](https://travis-ci.org/BowdoinOrient/libsass-python)

**UPDATE, 2/11/2015:** [Release 0.6.2 of dahlia/libsass-python](https://github.com/dahlia/libsass-python/releases/tag/0.6.2) removes the GCC (G++) 4.8+, LLVM Clang 3.3+ requirement, meaning C++ 11 is no longer required and the original fork can now be installed just fine on Ubuntu Precise out of the box. As such, this fork is no longer neccessary, and will not updated or maintained.

*Original README:*

A fork of [dahlia/libsass-python](https://github.com/dahlia/libsass-python) which does not require C++ 11. Use this fork if you want to compile Sass to CSS on Heroku, Debian Wheezy, or Ubuntu Precise without any Node or Ruby in your stack or compiling GCC/G++ from source.

Not tested on Windows.