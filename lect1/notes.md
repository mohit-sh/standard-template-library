Lecture 1:
- Just like python, there can be multiple implementations of the C++ Standard. One of them is the Visual Code.
- Standard Template Library focuses on 
    1. Fast
    2. Correct
 while being general purpose.
- Three main components of STL are:
    1. Containers
    2. Iterators
    3. Algorithms
 The algorithms don't directly interact with the containers, but through the iterators. Compatibility of an algorithm and a container depends on whether the iterator exposed by the container
 satisfies the constrains set by the algorithm. e.g. sort only works with containers that provide random access iterators.

- NOTE: For some problems, you might be tempted to resort to C like containers. Resist it and rely on the STL
- Iterators are essentially better behaved pointers.
