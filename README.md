# Fatigue-analysis-Lattices 2d

A progressive failure fatigue analysis of lattices

The Python 3 code uses a progressive failure approach to analyze 2D lattices.
Every lattice element is discretized as beam structure.
The FE calculation uses the directory Anastruct by https://github.com/ritchie46/anaStruct/blob/master/anastruct/basic.py
to evaluate displacements of bem elements.

The program makes iterative fatigue calculations on lattice structure removing minimum life elements.

