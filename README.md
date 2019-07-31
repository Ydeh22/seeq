# SeeQ

## Introduction

SEEQ is "See Quantum" the Self-explanatory library for Quantum Optics and
Quantum Mechanics

It is a collection of Jupyter notebooks that use literary programming Python
implementation of traditional and modern algorithms in Quantum Mechanics and
Quantum Optics.Matrix-Product-State algorithms. These include:

* A pythonesque interface to evolve a quantum state with constant or
  time-dependent Hamiltonians.
* Algorithms to study stationary and time-dependent master equations.
* Chebyshev and Lanczos approximations to the exponentials of unitary matrices.
* An implementation of quantum control with parameterized pulses.

The main goal of this library is not performance, but rapid prototyping and
testing of ideas, providing a good playground before dwelling in more advanced
(C++, Julia) versions of the algorithms.

## Requirements

The library is entirely developed in Python 3 using Numpy and Scipy, and a
standard Jupyter environment. We recommend using Anaconda3 or Miniconda3,
although any other distribution of Python should suffice.

## Usage

The library is explained in the self-contained notebooks with brief explanations
of the algorithms, the basic code, examples and tests. You can open the
notebooks and execute them. Each of them is self-contained, although it may rely
on other components of the library.

The library itself lives in the `seeq/` directory. It consists of various
modules and functions. The library is built from the Jupyter notebooks using
`make all`.

Version: 0.0

Authors:
* Juan José García Ripoll (Institute of Fundamental Physics)
