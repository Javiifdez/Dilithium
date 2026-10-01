# CRYSTALS-Dilithium Implementation

Post-Quantum Cryptography: Universidad Francisco de Vitoria (UFV)

**Authors:** Javier Fernández Meroño, David Sanz Fuertes, María Rivas Ramos

## Overview

Dilithium is a quantum-resistant digital signature scheme, standardized by NIST as **ML-DSA** in **FIPS 204**. Its security is based on problems over module lattices (**Module-SIS** and **Module-LWE**), rather than on integer factorization or the discrete logarithm problem, which a quantum computer would break.

This repository contains a **SageMath/Python** implementation of the scheme's three operations (KeyGen, Sign, Verify), using the **Fiat-Shamir with aborts** technique to prevent signatures from leaking information about the secret key.

## Contents

- `Implementacion.ipynb`: SageMath notebook with the full implementation and a sign/verify test.

## Requirements

- [SageMath](https://www.sagemath.org/)
