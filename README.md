# Hi! Welcome to my Python numpy repository
This [repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories) contains all of my Python NumPy (Numerical Python) tutorial. Each of the Python NumPy tutorials will have their own [branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches).

# What is NumPy?
NumPy is a fundamental package in Python for scientific computation (meaning it provides functionalitiy like efficient data structure, vectorization and broadcasting, shape manipulation, and advanced mathematical operations for scientific tasks). It is a Python library that provides multidimensional array object (a general term for 1D, 2D, and 3D arrays) along with tools for fast operations on array, shape manipulation, sorting, basic linear algebra, basic statistical operations, and many more. 

At the core of the NumPy package, is the `ndarray` object. This encapuslates n-dimensional array of homogeneous data type, with many operatins being performed in compiled code for performance. There are several differences between NumPy arrays and Python's built-in `list` type:
- **Fixed type and data type**:
  - NumPy arrays have fixed type at creation. Changing the of an `ndarray` will create a new array and delete the previous array.
  - All the elements in NumPy array are required to be of the same data type, and thus will be the same size in memory. Mixed data types are also possible but come with limitations, such as losing too many useful `ndarray` methods.

- **Efficient memory usage**:
  - NumPy arrays are way efficient when it comes to memory, because in most cases, NumPy array elements required to be the same elements. Whereas a Lists, can contain mixed data types, and those mixed data types will have a diffent size in memory and pointer to each Python's object.

- **Advanced mathematical operations**:
  - NumPy facilitates advanced mathematical operations (e.g., `+`, `-`, `/`, `*`, `**`, mean, etc).

For more comprehensive informations about NumPy array, please consider visit the [offical website doccumentation](https://numpy.org/doc/stable/user/whatisnumpy.html#whatisnumpy), or the other alternative information is the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/02.00-introduction-to-numpy.html).
