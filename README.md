# SO-3-to-SU-2-
Take a general special orthogonal 3x3 matrix and determine the local special unitary 2x2 matrix that induces it on a two-qubit state.

The code is available in mathematica and python.

In the python code, there are two functions for calculating the SU(2) from a given SO(3): get_su2_trminus1 and get_su2. get_su2 is for when the trace of the SO(3) matrix is not equal to -1. get_su2_trminus1 is for when the SO(3) matrix has trace equal to -1.
