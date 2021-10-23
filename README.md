# H3Fsymbols
These are the F-symbols for the H3 fusion category (see https://arxiv.org/abs/1906.01322). There are two parameters in the solution (p1 and p2) which are either +1 or -1, so there are four different solutions. In each of these solutions all elements are real numbers.

The solution has been obtained by solving the Pentagon equation with Mathematica (see the file "H3pentagon.nb") and exploiting properties of trivalent categories.

The solutions is stored in the file "Fsymbols_solution.m" as a list of rules. The notation is as follows: $F[a,b,c,d][e,f]$ corresponds to the matrix element $(F_a^{bcd})_{ef}$.

With the file "VerifySolution.nb" it can be verified that the solution fulfils the pentagon equation and that the matrices are unitary.
