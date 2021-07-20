# SDSC HPC User Training Notebook Catalog: CUDA_GPU
# Notebook Names: 
* CUDA_GPU_computing_pi.ipynb
* CUDA_GPU_computing_pi_solution.ipynb
* CUDA_GPU_distance_matrix.ipynb
* CUDA_GPU_distance_matrix_solution.ipynb
* CUDA_GPU_law_of_cosines.ipynb
* CUDA_GPU_law_of_cosines_solution.ipynb
# Locations:
* [computing_pi.ipynb](./CUDA_GPU_computing_pi.ipynb)
* [computing_pi_solution](./CUDA_GPU_computing_pi_solution.ipynb)

* [distance_matrix.ipynb](./CUDA_GPU_distance_matrix.ipynb)
* [distance_matrix_solution](./CUDA_GPU_distance_matrix_solution.ipynb)

* [law_of_cosines.ipynb](./CUDA_GPU_law_of_cosines.ipynb)
* [law_of_cosines_solution.ipynb](./CUDA_GPU_law_of_cosines_solution.ipynb)
# Date (last updated): June 2021
# Python Package Dependencies: 
CUDA, math, numba, numpy
# Keywords
data, ufuncs
# Short Description
In the Computing Pi exercise, we will design a CUDA kernel to compute the value of Pi 
via Monte Carlo.  The concepts of writing and invoking CUDA kernels in 
Numba are introduced.

In the Distance Matrix exercise, we will compute a distance matrix for a synthetic dataset of 
3-D molecular geometries.  We will learn how to leverage higher-dimensional
CUDA thread-block hierarchies.

In Law of Cosines exercise, we will explore GPU Ufuncs which are simple to write, invoke, 
and are compatible with Numpy Ufuncs.  We will learn how to write a simple GPU 
Ufunc to compute the law of cosines.

# References
Below are litsed a few related readings and presentations.
[Numba](http://numba.pydata.org/) supports CUDA GPU programming by directly 
compiling a subset of Python code into CUDA kernels and device functions 
following the CUDA execution model.  

In the provided notebooks, a problem is introduced and mostly implemented in 
Numba.  As an exercise, complete the missing lines of code to successfully 
compute the result.  

These notebooks were part of th SDSC HPU User Training Spring 2020 Session Week 4 (01/31/2020) and were **presented by Abe Stern, NVIDIA** with the topic of **GPU accelerated computing with CUDA Python**.

