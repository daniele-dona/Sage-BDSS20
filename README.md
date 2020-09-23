# Sage-BDSS20
SageMath code for "Symplectic Hypergeometric Groups of Degree Six" (Bajpai, Dona, Singh, Singh)

The code deposited here refers to a SageMath program referring to the paper "Symplectic Hypergeometric Groups of Degree Six" (to appear in J. Algebra, available as arXiv:2003.10191v2), by Jitendra Bajpai, Daniele Dona, Sandip Singh, and Shashank Vikram Singh.

The program is written in SageMath, version 8.9: the computations are quite elementary and could have been performed by programs in other languages as well but SageMath is open-source which is why we chose to use it.

The program is designed to take two polynomials f,g and an integer k, and find whether there exists some γ∈Γ(f,g) satisfying the hypotheses of Proposition 1 and that can be written as a product of at most k matrices in {A,B,A^{−1},B^{−1}}, where A and B are the companion matrices of f and g respectively. Example values have already been inserted, with f=Φ_1(x)^6, g=Φ_3(x)^2·Φ_6(x) and k=9, corresponding to the parameters appearing in entry 17 of Table A; an interested reader only needs to modify these values to use the code for themselves (in the last line of the Sage code). The code is commented throughout, to improve legibility and verifications.
