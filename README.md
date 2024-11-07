# Post Quantum Cryptography - Scala #

A small library for use within the Simex messaging protocol (SEP) client and server.

See [NIST](https://csrc.nist.gov/projects/post-quantum-cryptography) for more information.
The aim of this project is to provide a set of key-based encryption and hashing functions that can be used in SEP clients and servers that are deemed secure against both quantum and classical computers. Currently, the two systems are considered in this project:

1. [FIPS-203](https://csrc.nist.gov/pubs/fips/203/final) Module-Lattice-Based Key-Encapsulation Mechanism Standard (ML-KEM)
2. [FIPS-204](https://csrc.nist.gov/pubs/fips/204/final) Module-Lattice-Based Digital Signature Standard
3. [FIPS-205](https://csrc.nist.gov/pubs/fips/205/final) Stateless Hash-Based Digital Signature Standard

It should be noted that these are currently considered PQC safe, but this can change. Hence, a standard set of APIs are provided that can be used in other projects but the underlying mechanism are subject to change as further research is carried out in Post-Quantum Cryptography.
