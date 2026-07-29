# hash-table #
This is a string hashtable of key-value pairs implementation in c++

A hash table implemented from scratch in C++ for string keys, using a custom polynomial rolling hash function instead of std::hash. Handles collisions via chaining and dynamically resizes based on load factor to maintain average O(1) lookup, insert, and delete.
Note: main.cpp is just a test file

## Usage ##
``` make string-hash-table ``` to compile

``` make run ``` to run
``` make val ``` to valgrind
