Blink
=====

Blink is a feature-rich SIP client created by [AG Projects](http://ag-projects.com/)
and has been one of my favourite apps since Snow Leopard. Even though the source
is GPL licensed and Qt based binary packages are available for free on Windows
and Linux, the Blink Cocoa for OSX costs a small fortune (IMHO).

This repository is a fork of the blink-cocoa darcs repository (from version 3.3.1)
in an attempt to create a free OSX binary.

Please refer to http://icanblink.com/ if you are looking for the version maintained
by the original author(s).


### Compiling from source

There are quite a lot of dependencies if you are to compile Blink from source.
I have bundled them for OSX 10.9 Intel (x64) which can be downloaded from
(here)[http://packages.geniusse.com/osx/10.9/blink/blink-deps-macosx-10.9-intel-x64.tar.bz].
Extract the tar and put the contents inside the Blink source directory so you
have `$(SRCROOT)/Distribution/Frameworks` and `$(SRCROOT)/Distribution/Resources`.

Once you have the dependencies extracted, you should be able to compile and run
without any issues (fingers crossed).

