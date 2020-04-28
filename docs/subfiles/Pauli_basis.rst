Pauli Basis
===========

This section describes a suitable basis to represent density matrices. All the calculations in the dm_simulator is performed in this basis.

Pauli Matrices
--------------
Pauli matrices are are a set of three :math:`2\times 2` complex Hermitian and unitary matrices. They are denoted by :math:`\sigma`.

.. math::
    \sigma_1 = \pmatrix{0&1\\1&0}\hspace{10pt} \sigma_2 = \pmatrix{0&-i\\i&0}\hspace{10pt} \sigma_3 = \pmatrix{1&0\\0&-1}


Apart form being Hermitian and Unitary these matrices follows the following identities

.. math::
    \sigma_i^2 = I \\
    [\sigma_a,\sigma_b] = 2i\epsilon_{abc}\sigma_c\\
    {\sigma_a,\sigma_b} = 2\delta_{ab}I

These matrices with the :math:`2\times 2` identity matrix constitutes the Pauli basis. Any :math:`2\times 2` complex matrices can be decomposed into linear combination of Pauli matrices and identity. Moreover, for Hermitian matrix the coefficients turns out to be real. i.e.

.. math::
    \forall H \in M_2(\mathbb{C}) \text{ and } H^{\dagger} = H \\ \exists c_i\in \mathbb{R} \mid H = \sum_{i=0}^{3} c_i \sigma_i
