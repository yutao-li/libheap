# libheap
here is an implementation of a general heap library, including trivial heap and indexed heap, which not only supports the usual <em>push</em> , <em>pop</em>, <em>peek</em> operations, but also <em>heapification</em>, <em>key modification</em>, <em>key deletion</em> and <em>self-defined comparator</em>.  

Indexheap is a significant heap structure which stores and sorts (index,key) pairs according to their key, it is essential in efficient implementation of Dijkstra's algorithm, Prim's algorithm and other variants.  

Meanwhile, it also includes implementation of [Disjoint set](https://en.wikipedia.org/wiki/Disjoint-set_data_structure)(totally irrevalent, just attaching because I am bored).  
## Acknowledgement
this library is coded by reference to [algs4](https://algs4.cs.princeton.edu/code/). Much appreciation!


documentation to be completed    
## Installation  
method 1: pip install --user libheap  
method 2: download this project, and run "python setup.py install"  
method 3: install anaconda, and run "conda install -c a870070392 libheap"
only support python3
