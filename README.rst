Byterun
-------

This is a pure-Python implementation of a Python bytecode execution virtual
machine.  I started it to get a better understanding of bytecodes so I could
fix branch coverage bugs in coverage.py.

Supported Python versions
-------------------------

Currently will pass all py27 tests but will fail some py38 tests. 
One should keep in mind the byte code might change for different versions 
of Python.
