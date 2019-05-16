# The Scientific Python ecosystem


Unlike Matlab, IDL, NCL, or R, Python does not come with a pre-bundled set of modules for scientific computing. Below are the building blocks that can be combined to obtain a scientific computing environment:


- **Interactive, exploratory work :** [Jupyter](https://jupyter.org/) offers an end-user environment for work, a component to embed in other systems to provide an interactive control interface, and an abstraction of these ideas over the network for interactive distributed and parallel computing.

- **Numerical arrays :** Most Python numerical codes today are based on the [NumPy library](https://www.numpy.org/). N-dimensional array object is the basic data structure that virtually all libraries understand as a common data interchange object. NumPy arrays have a rich Python interface, but they also can be integrated with C, C++, and Fortran codes, making it easy to optimize performance bottlenecks or reuse existing libraries that have no knowledge of Python.

- **Data visualization :** [Matplotlib](https://matplotlib.org/) is the most widely used library for high-quality plotting, with support for a wide array of 2D and 3D plot types, precise layout control, a built-in LaTeX typesetting engine for label equations, and publication-quality output in all major image formats. Matploblib was used to produce [the first image of a black hole using data from the Event Horizon telescope](https://iopscience.iop.org/article/10.3847/2041-8213/ab0c57/meta). [The Holoviews library and its extensions](http://holoviews.org/) are often used for  building graphical interactive interfaces that tightly couple data visualization to user controls.

- **Algorithms :** [The SciPy package](www.scipy.org) provides a powerful collection of tools, both by wrapping existing libraries such as Lapack, FFTPack (a Fortran subroutine library of fast Fourier transforms), and the Arnoldi Package (ARPack), and with new code written for SciPy itself. SciPy has support for dense and sparse linear algebra, signal processing, optimization, numerical integration and ordinary differential equations, special functions, statistics, data !tting, and much more.

[The Scikits](http://scikits.appspot.com/scikits) project offers add-on packages for  SciPy, developed by teams focused on a speci!c application domain; today there are Scikits for image processing, time series analysis, statistical model description, environmental time series manipulation, machine learning, and more.

- **Performance :**  Fortran codes (such as those included in SciPy) have been traditionally accessed via f2py, a tool that generates Python wrappers for Fortran libraries included with NumPy. Projects such as [Cython](https://cython.org/), [Numba](http://numba.pydata.org/) are used to optimize Python code.

- **Parallel and Distributed Computing :** [The Dask library and its ecosystem](https://dask.org/) are widely used for running the same Python code on more than one machine, building [microservices](https://en.wikipedia.org/wiki/Microservices) and [actors](https://en.wikipedia.org/wiki/Actor_model) that have state and can communicate, efficiently handling large objects and numerical data.


- **Symbolic manipulation:** Python doesn’t have a native notion of symbols like languages such as Mathematica, but [the Sympy package](www.sympy.org) offers basic symbolic objects and a growing collection of symbolic manipulation tools, from simple algebra to Gröbner bases.
