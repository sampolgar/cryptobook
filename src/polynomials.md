Polynomial Blog Post

Polynomials in ZK-Snarks
• Quick purpose of ZK-SNARK
o Verifying is faster than computing (give an example)
o What succinctness means and why its important (size of proof grows slower than computation)
o How life would look like without succinct proofs
o How polynomials make this all possible
o Where they’re used include Polynomial IOP, Groth16, Sumcheck
o How we use them, what properties? Secret sharing, Identity testing

How interaction between prover and verifier works in a snark

- Prover is a polynomial, Verifier queries are evaluation points
- Introduce some ways a prover can prove things about their polynomial

Mathematical Properties of ring polynomials https://en.wikipedia.org/wiki/Polynomial_ring#Polynomial_evaluation
• Roots
• Right homomorphism and operations
• Evaluation
• Interpolation

Proving methods / mathematical properties used to prove. How to get fancy
• Different ways a polynomial can be used to prove things
o Coefficients
• Knowledge of a constrained polynomial
• Different ways to constraint a polynomial
• Ensuring the prover uses a polynomial (Lowest Degree Test)
• Homomorphism

Resources
• Schwartz Zippel Lemma: dankrad fiest https://dankradfeist.de/ethereum/2023/08/08/sumcheck-quickie.html
• https://hackmd.io/@vbuterin/snarks#An-approximate-introduction-to-how-zk-SNARKs-are-possible
