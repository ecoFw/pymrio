pymrio
======

A python module for automating input output calculations and generating reports.

This is work in progress, so far only tested for the EXIOBASE 2.0 system (CREEA project). However, in principal pymrio can handle any symetric mrio table (e.g. WIOD, EXIOBASE 1.0).

Usage
-----

A small test mrio is included in the package. To use it call

    import pymrio
    test_mrio = pymrio.load_test()

The test_mrio consists of a transaction matrix and two extension types.

Check the doc and the tutorial for further information


Installation
------------

Up to now now pymrio doesn't have a installation routine. Just download the package from the source repository (download zip on right toolstrip) and add the folder to your python path. 

import sys
_pymrio_path = r'D:\KST\proj\pymrio\pymrio'  
if not _pymrio_path in sys.path:
    sys.path.append(_pymrio_path)
del _pymrio_path

Dependencies
------------

- Python 3.0 or later
- pandas
- numpy
- scipy
- matplotlib
- docutils (only for generating reports in html format)