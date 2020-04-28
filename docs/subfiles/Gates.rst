Gates
=====

Gates are similar to the logic gates for bits. Because of the linearity it is enough to know the action of the gate on the basis elements, for one qubit :math:`|0\rangle` and :math:`|1\rangle`. For example a not gate takes :math:`|0\rangle` to :math:`|1\rangle` and vice versa. To get the visual picture in Bloch sphere, the arrow goes to the antipodal point after acted upon by a not (X) gate. For a general gate acting on one qubit implies a rotation of the arrow around the sphere. Different gate encodes different rotations.

Matrix Represantation
---------------------
Now coming back to the example of the not gate. For a general qubit state the gate have the following action

.. math::
    X(a|0\rangle + b|1\rangle) = a X|0\rangle + b X|1\rangle = b|1\rangle + a|0\rangle \\
    X\pmatrix{a\\ b} = \pmatrix{b \\ a} = \pmatrix{0&1\\ 1&0}\pmatrix{a \\ b}

This way we can write the gate as a matrix acting on the state. Below some example are given for different common gates

- **Hadamard Matrix**
    :math:`H = \pmatrix{1&-1\\ -1&1}`
- **Pauli Matrices**
    + :math:`X = \pmatrix{0&1\\ 1&0}`
    + :math:`Y = \pmatrix{0&-i\\ i&0}`
    + :math:`Z = \pmatrix{1&0\\ 0&-1}`
- **Rotation Matrix**
    + :math:`U_1() = \pmatrix{}`

Multi-Qubit Gates
-----------------
