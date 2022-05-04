1)What makes numpy. shape()different from numpy.size()?

A)Shape() is used to get complete structural shape of our 2Darray.
For example(3,4). np. size() will give us how many elements are present in total.

2)In Numpy, describe the idea of broadcasting?

A) The term broadcasting refers to ability of Numpy  to treat arrays
Of different shapes during arthimetic operations. Arthimetic operations on arrays are usually done on corresponding elements. If two arrays are of exactly the same shape, then these operations are smoothly performed.

3)What makes python better than other libraries for numerical computation?

A)One of the key features of python is its numerous libraries and packages. Some are written in given below.
 
 1)SciPy:
The SciPy package includes algorithms and functions which are crux of python scientific computing capabilities.

The sub-package includes:
*io: Used for the standard input and output.
*lib: This function is used to wrap python external libraries.
*signal: Used for processing signal tools
2)Pandas:
Pandas is the most important data analysis library of python.Being open source,it is used for analysing data with python.

The following codes can be run to implement different operations on pandas.

*Import pandas as pd, it is highly suggested to import the library as pd.
*pd.read_filetype()(to open the desired file)
*pd.data frame()(to convert a specified python object)

3)Numeric python:
Numpy guarantee swift execution as it is accumulated with applications and services that can understand and analyse human languages and data.

We need to import Numpy into memory to perform numerical operations.

*Import numpy as np.
*A_values=[20,30,40,50]
*A=np.array
*print(A)
*print(A*9/5+32)

4)How does Numpy deal with files?

A)Numpy introduces a simple file format for ndarray objects.This .npy file stores data, shape, dty And other information required to reconstruct the ndarray in a disk file such that the array is correctly retrieved even if the file is on another machine with different architecture. 

5)Mention the importance of NumPy .empty()

A)The empty() function is used to create a new array of given shape and type,without initializing entries.Shape of the empty array, e.g (2,3) or 2.Desired output data type for the array,e.g,numpy .int8.














