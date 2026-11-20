# Cryptography and Coding Coursework

Julia code developed for the Cryptography and Coding course at Imperial College London. The coursework implements number-theoretic and algebraic algorithms and applies them to public-key cryptography and error-correcting codes.

## Repository structure

| Folder | Content |
|---|---|
| `1 Coursework` | Modular arithmetic, primality testing and factorisation |
| `2 coursework` | Public-key cryptography and finite fields |
| `3 coursework` | Linear codes: Hamming and Reed–Solomon codes over finite fields |

## Topics covered

### Number theory and cryptography (Courseworks 1–2)

- **Modular arithmetic**: modular exponentiation and division.
- **Primality and factorisation**: Miller–Rabin primality testing and Pollard’s rho algorithm.
- **Primitive roots and discrete logarithms**: finding generators and solving discrete logarithm problems.
- **Public-key cryptography**: RSA key generation and encryption, Diffie–Hellman key exchange, and ElGamal encryption and digital signatures.
- **Finite fields and polynomials**: Lagrange interpolation, polynomial arithmetic, and primitive elements in finite fields.

### Error-correcting codes (Coursework 3)

- **Binary Hamming codes**: construction of the parity-check matrix in lexicographic order, systematic generator matrix, syndrome decoding of single errors, and decoding of up to two erasures.
- **Channel analysis**: decoding error probability over the Binary Symmetric Channel and decoding failure probability over the Binary Erasure Channel.
- **Linear algebra over finite fields**: construction of 𝔽_q = 𝔽_p[u]/(f(u)) and matrix inversion via the adjugate matrix.
- **Reed–Solomon codes over 𝔽₃₂**: generator and parity-check matrices, syndrome computation, solution of the key equation with the extended Euclidean algorithm, Chien search for error locations, Forney’s formula for error values, and recovery of the transmitted message.

## Using the code

Courseworks 1 and 2 are Julia scripts (`.jl`), and Coursework 3 is a Jupyter notebook (`.ipynb`) with a Julia kernel.

**Requirements:** Julia, with the packages `Nemo.jl`, `AbstractAlgebra.jl`, `LinearAlgebra` and `JLD2.jl`. Jupyter (via `IJulia.jl`) is needed for the notebook.

- **Scripts:** load the relevant function definitions first, then run the corresponding exercise block.
- **Notebook:** run the cells from top to bottom.

Exercises that use coursework-provided inputs need the corresponding personalised data file, which is not included in this repository.
