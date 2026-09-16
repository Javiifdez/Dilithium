# Implementación de CRYSTALS-Dilithium

Criptografía Poscuántica — Universidad Francisco de Vitoria (UFV)

**Autores:** Javier Fernández Meroño, David Sanz Fuertes, María Rivas Ramos

## Resumen

Dilithium es un esquema de firma digital resistente a ataques cuánticos, estandarizado por el NIST como **FIPS 204**. Su seguridad se basa en problemas sobre retículas modulares (**Module-SIS** y **Module-LWE**), en lugar de la factorización o el logaritmo discreto que rompería un ordenador cuántico.

Este repositorio contiene una implementación en **SageMath/Python** de las tres operaciones del esquema (KeyGen, Sign, Verify), usando la técnica de **Fiat-Shamir con abortos** para evitar que la firma filtre información sobre la clave secreta.

## Contenido

- `Implementacion.ipynb` — Notebook de SageMath con la implementación completa y una prueba de firma/verificación.

## Requisitos

- [SageMath](https://www.sagemath.org/) 
