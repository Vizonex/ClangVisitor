# ClangVistor
Inspired by Cython's Own Compilers and Nodes, This Tool is made to help With Lower-level parsing with Clang and helps with compiling and reading off 
certain portions of different ast code via cursors.

- I found it incredably annoying that all the other cython binding libraries are rather dull and not currently being maintained.
- libclang does not have very good static typechecking (Hence writing these visitors to begin with)

- I would like to develop Cython Nodes based their own base-class in the future for libclang so that writing Visitors will be easier
for some users as well as for acessing thinsg such as struct members or C++ functions along with their full function signatures.




