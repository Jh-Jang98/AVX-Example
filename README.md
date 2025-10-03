# AVX Example Repository

This repository contains example codes that demonstrate the use of Intel AVX/AVX2/AVX-512 SIMD intrinsics.  
The goal is to learn and experiment with vectorized operations such as vector addition, multiplication, dot products, and other compute kernels that benefit from SIMD acceleration.

---

## 🚀 Features
- Example codes using Intel AVX intrinsics
- Vectorized arithmetic operations (add, mul, dot product, etc.)
- Performance comparison with scalar (non-SIMD) implementations
- Covers AVX, AVX2, and AVX-512 instructions

---

## 📂 Directory Structure
```
.
├── avx/ # AVX examples
├── avx2/ # AVX2 examples
├── avx512/ # AVX-512 examples
└── benchmark/ # Performance comparison codes
```
---

## ⚙️ Requirements
- **CPU**: Intel processor with AVX support (Sandy Bridge or later)  
- **OS**: Linux / Windows / macOS (Intel only)  

Build examples with:
```bash
# AVX
gcc -O2 -mavx -o avx_example avx_example.c

# AVX2
gcc -O2 -mavx2 -o avx2_example avx2_example.c

# AVX-512
gcc -O2 -mavx512f -o avx512_example avx512_example.c
