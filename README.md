# Compression Algorithms

## Introduction
Compression algorithms usually explore some sort of pattern or structure in its input. 

Huffman encoding explores the distribution of the symbols of the alphabet of the input. 
This means that a random generator of bits decompressed by a huffman decoder would equate the distribution of base symbols of language

Claude Shannon proposed [this](https://www.cs.princeton.edu/courses/archive/fall13/cos126/assignments/markov.html) idea that provides a very qualitative way to test how good a compression algorithm works: 
Decode a random stream of bits and observe how similar this is to a sample of the domain


