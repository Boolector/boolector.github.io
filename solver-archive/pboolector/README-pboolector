These are the sources of the prototype implementation for pBoolector,
a parallel implementation of the SMT solver Boolector based on bit-blasting
and look-ahead for QF_BV. 

This version (pboolector-0.0) was developed by Christian Reisenberger as
a master's thesis and will not be maintained in the future.
For more information on the approach implemented in pBoolector see [1].

Note that the pBoolector sources as provided here are an extension to the SMT
solver Boolector version 2.0.1 (download at [2]).


To compile, first download and unpack boolector-2.0.1 from [2] and copy all
source files and the pBoolector make file into the Boolector source directory.
Apply pboolector.patch (provided with the pBoolector sources) as follows:
  patch --ignore-whitespace < pboolector.patch

Next add the following line to 'makefile.in':
  -include pboolector.mk

Now issue './configure && make'. This will build the solver pboolector.



The file VERSION contains the current version number.

The file NEWS lists history and latest changes.

THESE SOURCES ARE FOR ACADEMIC USE ONLY.
USE IN COMPETITIONS IS RESTRICTED TOO.
SEE 'COPYING' FOR MORE DETAILS.

[1] http://fmv.jku.at/master/Reisenberger-MasterThesis-2014.pdf
[2] http://fmv.jku.at/boolector/boolector-2.0.1-with-lingeling-azd.tar.bz2
