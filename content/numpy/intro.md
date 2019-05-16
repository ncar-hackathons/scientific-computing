# Introduction

- NumPy provides the numerical backend for nearly every scientific or technical library for Python. In fact, NumPy is the foundation library for scientific computing in Python since it provides data structures and high-performing functions that the basic Python standard library cannot provide. Therefore, knowledge of this library is essential in terms of numerical calculations since its correct use can greatly influence the performance of your computations.

- NumPy provides the following additional features:
   - `Ndarray`: A multidimensional array much faster and more efficient
than those provided by the basic package of Python. The core of NumPy is implemented in C and provides efficient functions for manipulating and processing arrays.

  - `Element-wise computation`: A set of functions for performing this type of calculation with arrays and mathematical operations between arrays.

  - `Integration with other languages such as C, C++, and FORTRAN`: A
set of tools to integrate code developed with these programming
languages.

- At a first glance, NumPy arrays bear some resemblance to Python’s list data structure. But an important difference is that while Python lists are generic containers of objects:
  - NumPy arrays are homogenous and typed arrays of fixed size.
  - Homogenous means that all elements in the array have the same data type.
  - Fixed size means that an array cannot be resized (without creating a new array).
