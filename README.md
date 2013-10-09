ZBar
====

ZBar is an open source software suite for reading bar codes from various sources, such as video streams, image files and raw intensity sensors. It supports many popular symbologies (types of bar codes) including EAN-13/UPC-A, UPC-E, EAN-8, Code 128, Code 39, Interleaved 2 of 5 and QR Code.

The purpose of this repository
==============================

This repository is forked from download [https://pypi.python.org/pypi/zbar/0.10](https://pypi.python.org/pypi/zbar/0.10).

Patches `imagescanner.c` to fix crashing (segmentation fault 11) issues with `import zbar` on OS X.

Patch taken from [http://launchpadlibrarian.net/134768014/zbar_0.10+doc-7build3_0.10+doc-8.diff.gz](http://launchpadlibrarian.net/134768014/zbar_0.10+doc-7build3_0.10+doc-8.diff.gz).

