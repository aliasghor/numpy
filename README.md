# Hi! Welcome to my Python numpy repository
This [repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories) contains all of my Python NumPy (Numerical Python) tutorial. Each of the Python NumPy tutorials will have their own [branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches).

# What is NumPy?
NumPy is a fundamental package in Python for scientific computation (e.g., provides efficient data structure, support mathemtical operations, broadcasting and vectorization, etc). It is a Python library that provides multidimensional array object (a general term for 1D, 2D, and 3D arrays), mathematical operations, shape manipulation, sorting, basic linear algebra, basic statistical operations, and many more that are useful for doing scientific things.

At the core of the NumPy package, is the `ndarray` object. This encapuslates n-dimensional array of homogeneous data type, with many operatins being performed in compiled code for performance. There are several differences between NumPy arrays and Python's built-in `list` type:
- NumPy array have fixed type. Therfore, changing the size of an array will create a new array and discard the previous array.
- The elements must be the same data type, and thus will be the same size in memory. It is also possible to have a different data type elements, but the size will not be the same in memory, and sacrifice all of the `ndarray` object methods that are useful for doing scientific things.
- NumPy array faciliate advanced mathematical operations (e.g., addition, substraction, division, multiplication, mean, sum, etc).

For more comprehensive informations about NumPy array, please consider visit the website doccumentation: [nump.org](https://numpy.org/doc/stable/).
