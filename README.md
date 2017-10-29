Xxxcoin integration/staging tree
================================

http://www.xxxcoin.org

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers

What is Xxxcoin?
----------------

Xxxcoin is a lite version of Bitcoin / litecoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~84 million total coins

The rest is the same as Bitcoin.
 - 50 coins per block
 - 2016 blocks to retarget difficulty


License
-------

Xxxcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------


Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake XXXCOIN_QT_TEST=1 -o Makefile.test xxxcoin-qt.pro
    make -f Makefile.test
    ./xxxcoin-qt_test

