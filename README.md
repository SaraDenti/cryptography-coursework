# Cryptography and Coding Coursework

Two Julia scripts developed for the Cryptography and Coding course at Imperial College London. The scripts implement number-theoretic algorithms and explore how they are used in public-key cryptography.

## Topics covered

- **Modular arithmetic** — modular exponentiation and division.
- **Primality and factorisation** — Miller–Rabin primality testing and Pollard’s rho algorithm.
- **Primitive roots and discrete logarithms** — finding generators and solving discrete logarithm problems.
- **Public-key cryptography** — RSA key generation and encryption, Diffie–Hellman key exchange, and ElGamal encryption and digital signatures.
- **Finite fields and polynomials** — Lagrange interpolation, polynomial arithmetic, and primitive elements in finite fields.

## Using the scripts

Open the two `.jl` files in a Julia editor. Check the `using` and `import` statements at the top of each script for its package requirements. Some exercises use `Nemo.jl` and `AbstractAlgebra.jl` for finite-field and polynomial computations.

To run individual examples, load the relevant function definitions first, then run the corresponding exercise block. Blocks that use coursework-provided inputs or variables require those inputs to be loaded or defined first.
