# Matrix Product State 
Matrix product state, also referred to as Tensor Train in the field of physics, offers a method to represent an N-dimensional tensor by decomposing it into a product of smaller dimensional tensors. This representation involves factorizing a tensor with N indices into a series of interconnected three-index tensors, forming a chain-like structure. The following image represents an MPS of a 6-dimensional tensor.

<img width="529" alt="Screenshot 2023-06-20 at 3 31 23 PM" src="https://github.com/PAYAL980/Matrix-Product-States-Preparation-/assets/71563541/2c645e1f-e730-48c4-ac36-ac71c251f524"> 

We tried to reproduce the results from the paper [1]. The authors have performed QFT using tensor networks for three different functions namely "cosine function", "20 cosine function", and "cosine + cusp function". The "cosine function" is the trigonometric cosine function with frequency 2π. The "20 cosine function" is a sum of 20 cosine functions with different frequencies. The "cosine + cusp" function is a sum of the cosine function and 4 exponential terms which forms a cusp-like shape, hence the name cosine + cusp function.

All of the code is written in Python and Quimb ’quantum information many-body' which is a fast Python library mainly for tensor networks. The repository contains the code for preparing the Matrix Product State and benchmarking it with classical state prep.

## References
[1] Jielun Chen, E. M. Stoudenmire, and Steven R. White. The quantum fourier transform has small entanglement, 2022.

[2] Johnnie Gray. quimb: a python library for quantum information and many-body calculations. Journal of Open Source Software, 3(29):819, 2018.
