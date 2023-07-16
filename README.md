# FCI Link Layer Authentication and Key Establishment Protocols Security Proofs via Tamarin

Formal security verification of the following protocols:
- FCI instantiation of the ISO/IEC 11770-3 KAM-7 protocol for initial authentication and key establishment
- FCI instantiation of the ISO/IEC 11770-3 SKTM-3 with ECIES and ECDSA for link layer handovers
- FCI instantiation of the ISO/IEC 11770-2 KEM-3 for link layer handovers reusing previously established security associations
- FCI instantiation of the ISO/IEC 11770-2 KEM-3 + ISO/IEC 11770-2 KEM-5 for link layer handovers
- FCI instantiation of the ISO/IEC 11770-2 KEM-3 for link layer handovers with Master Key (MK) based KDF


## Author

Nils Mäurer: Institute of Communication and Navigation, German Aerospace Center (DLR), Wessling, Germany

## Paper

N. Mäurer, T. Ewert, T. Gräupl, K. Morioka, N. Kanada and C. Schmitt. A Combined Link Layer Security Solution for FCI Datalink Technologies. 
In 2023 IEEE/AIAA 42nd Digital Avionics Systems Conference (DASC), pages 1–10, Barcelona, SPA, 2023

## The Tamarin prover repository

For installation and usage instructions of the Tamarin prover see chapter 2 of the manual:

https://tamarin-prover.github.io/manual/book/002_installation.html

## Build environment

Tamarin prover: v1.6.1

OS: Windows 10 with WSL 2.0 - Ubuntu 20.04

Configuration: Intel(R) Core(TM) i7-8850U CPU 64GB of RAM

All proofs were done with tamarin-prover version 1.6.1.

Please note: The proofs can take up to 60GB of RAM.
