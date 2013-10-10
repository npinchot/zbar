ZBar
====
ZBar is an open source software suite for reading bar codes from various sources, such as video streams, image files and raw intensity sensors. It supports many popular symbologies (types of bar codes) including EAN-13/UPC-A, UPC-E, EAN-8, Code 128, Code 39, Interleaved 2 of 5 and QR Code.

The purpose of this repository
==============================
This repository is forked from the [ZBar python wrapper download at PyPI](https://pypi.python.org/pypi/zbar/0.10), and only contains the python wrapper for the C library. For the full C library source, installation directions, etc., check out the [ZBar homepage](http://zbar.sourceforge.net).

Fixes implemented
===================
[Patches `imagescanner.c`](https://github.com/npinchot/zbar/commit/d3c1611ad2411fbdc3e79eb96ca704a63d30ae69) to fix crashing (segmentation fault 11) issues with `import zbar` on OS X.

Patch taken from [http://launchpadlibrarian.net/134768014/zbar_0.10+doc-7build3_0.10+doc-8.diff.gz](http://launchpadlibrarian.net/134768014/zbar_0.10+doc-7build3_0.10+doc-8.diff.gz).

