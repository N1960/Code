This repository contains a Magma implementation of the **x-superoptimal pairing** on the **BW curves** with embedding degrees **10** and **14**, and  
 of the final exponentiation step on **BLS12 curve**, using new defined parameters, focusing on optimizing the **final exponentiation step**. 

## Overview

The x-superoptimal pairing is a variant of optimal pairings, 
designed to reduce the computational cost of pairing-based cryptographic operations. 
This project explores its application on two specific pairing-friendly elliptic curves:
- BW10 (embedding degree 10)
- BW14 (embedding degree 14)

The core focus lies in:
- Defining specific curve parameters for BW10 and BW14
- Implementing the Miller loop
- Optimizing the final exponentiation step with cost-effective exponentiation chains
