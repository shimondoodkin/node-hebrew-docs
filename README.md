Translation of Node.js Docs to hebrew
===

### Translation Method
 * __To work in branch__ *hebrew-docs*
 * After node.js docs has been updated to use *git rebase* (the exect git command not known yet - write it here in readme)

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
 # build node.js first
 # run
    make doc
