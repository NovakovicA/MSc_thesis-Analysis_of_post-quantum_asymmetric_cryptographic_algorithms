# MSc thesis - Analysis of post-quantum asymmetric cryptographic algorithms

Analysis of the current standard asymmetric algorithms for key exchange (DH, RSA, ECDH, ECIES, ElGamal), of their vulnerability towards a sufficiently powerful quantum computer using Shor's algorithm and the analysis of NIST post-quantum finalist algorithms for key exchange from round 3 of the competition (Classic McEliece, CRYSTALS-Kyber, NTRU, Saber). 

Application implemented in C++ for analyzing performance and memory requirements for analyzed standard and post-quantum asymmetric algorithms for key exchange.
Crypto++ and liboqs with C++ extensions are the libraries used to include secure implementations of these algorithms within the project.
The thesis is written in Serbian, while the application code/output is in English.

Supported algorithms and parameters:
- Anonymous Diffie-Hellman (supported key sizes: 1024, 2048, 4096, 8192 b)
- Ephemeral Diffie-Hellman (supported key sizes: 1024, 2048, 4096, 8192 b)
- Elliptic Curve Diffie-Hellman with Curve25519
- RSA with OAEP padding scheme
- Elliptic Curve Integrated Encryption Scheme with curve secp256r1
- ElGamal (supported key sizes: 1024, 2048, 4096, 8192 b)
- Classic-McEliece-348864
- Classic-McEliece-348864f
- Classic-McEliece-460896
- Classic-McEliece-460896f
- Classic-McEliece-6688128
- Classic-McEliece-6688128f
- Classic-McEliece-6960119
- Classic-McEliece-6960119f
- Classic-McEliece-8192128
- Classic-McEliece-8192128f
- Kyber512
- Kyber768
- Kyber1024
- Kyber512-90s
- Kyber768-90s
- Kyber1024-90s
- NTRU-HPS-2048-509
- NTRU-HPS-2048-677
- NTRU-HPS-4096-821
- NTRU-HPS-4096-1229
- NTRU-HRSS-701
- NTRU-HRSS-1373
- LightSaber-KEM
- Saber-KEM
- FireSaber-KEM
