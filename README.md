deepy: Highly extensible deep learning framework based on Theano
===

[![Build Status](https://travis-ci.org/uaca/deepy.svg)](https://travis-ci.org/uaca/deepy)

Many codes are still not well documented.

Raphael Shu

Run with following setting
===

```
PYTHONPATH="." THEANO_FLAGS='floatX=float32,nvcc.fastmath=True,openmp=True,openmp_elemwise_minsize=1000' \
OMP_NUM_THREADS=8 python ...
```
