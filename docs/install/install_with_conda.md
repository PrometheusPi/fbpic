Installation of FBPIC  on the Anaconda Python distribution
=======================================

Overview
-------

Anaconda is a convenient distribution of Python. However, it does not
have the packages `pyfftw` and moreover the package `mpi4py` is buggy.

This file describes how to install `pyfftw` in `mpi4py` in this case.

Installation of `pyfftw`
-------------------

`conda install -c https://conda.anaconda.org/mforbes pyfftw`

Bug fix  of `mpi4py` on OSX
------------------------

If the following command crashes
`>>> from mpi4py import MPI`
it can be fixed by typing
`sudo ln -s ~/anaconda /opt/anaconda1anaconda2anaconda3`