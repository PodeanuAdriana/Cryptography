# Cryptography
My projects include the implementation of both classical and modern encryption and decryption algorithms, developed in C++. These cover a wide range of cryptographic techniques, from simple substitution and transposition methods to more complex algorithms, such as DES. My goal was to create an efficient platform for experimenting with and understanding these techniques.
I implemented character shifting encryption and support for texts with special characters using the Caesar cipher. The substitution cipher, which uses a defined permutation of the alphabet and checks for valid keys, was also implemented. For the Affine cipher, I used linear functions and the extended Euclidean algorithm to calculate the modular inverse and ensure correct encryption.
Encryption and decryption based on a repetitive key applied to the text were achieved through the Vigenère cipher. The Hill cipher works with matrices and includes checks for the determinant and modular inverse of matrices.
The Extended Euclidean Algorithm: This calculates the GCD and modular inverse, used in algorithms like Affine and Hill.
For DES (Data Encryption Standard), I implemented standard steps such as permutations, substitutions, and the Feistel function for symmetric block encryption. The chosen language for implementation is C++.

