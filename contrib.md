## Third Party Contributions

### Partial Haskell Bindings

[https://github.com/jwaldmann/haskell-boolector](https://github.com/jwaldmann/haskell-boolector)
by [Johannes Waldmann](http://www.imn.htwk-leipzig.de/%7ewaldmann)

### Benchmarks

[BEEM benchmarks in BTOR format](http://fmv.jku.at/aiger/index.html#beem) by Jori Dubrovin


### pBoolector

The following sources represent the prototype implementation pBoolector.
It was implemented by Christian Reisenberger for his
[master's thesis](http://fmv.jku.at/master/Reisenberger-MasterThesis-2014.pdf)
as an extension of
Boolector version
[2.0.1](solver-archive/boolector-2.0.1-with-lingeling-azd.tar.bz2)
and will <b>not be maintained</b> in the future.

[pboolector-0.1.tar.gz](solver-archive/pboolector/pboolector-0.1.tar.gz)

pBoolector is a parallel implementation of Boolector
based on bit-blasting and look-ahead
for QF_BV.
It is available under a restricted
[license](solver-archive/pboolector/COPYING-pboolector.txt)
for non-commercial use.
See the
[COPYING](solver-archive/pboolector/COPYING-pboolector.txt)
and [README](solver-archive/pboolector/README-pboolector.txt)
files provided with the sources for license information and more detailed
information on how to patch Boolector version
[2.0.1](solver-archive/boolector-2.0.1-with-lingeling-azd.tar.bz2)
with the provided pBoolector sources.

<b>Note:</b> The pBoolector sources are provided as an extension to
Boolector version
[2.0.1](solver-archive/boolector-2.0.1-with-lingeling-azd.tar.bz2)
and are not compatible with earlier or later releases of Boolector.




