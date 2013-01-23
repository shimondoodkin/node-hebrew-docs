Translation of Node.js Docs to hebrew
===

### Translation Method
 * work in branch hebrew-docs
 * after node doces has been updated to use git rebase (the git command not known yet - write it here in readme)

### To build:

Prerequisites (Unix only):

    * Python 2.6 or 2.7
    * GNU Make 3.81 or newer
    * libexecinfo (FreeBSD and OpenBSD only)

Unix/Macintosh:

    ./configure
    make
    make install

Windows:

    vcbuild.bat

### To run the tests:

Unix/Macintosh:

    make test

Windows:

    vcbuild.bat test

### To build the documentation:

    make doc
