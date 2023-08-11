# Huffman
This project implements the Huffman coding algorithm in C++, a classic approach for lossless data compression. Huffman coding involves creating variable-length codes for input characters, where more frequent characters are assigned shorter codes. 

Since I have been doing CP and practicing DSA for a while now, I wanted to implement the concepts of DSA to create some projects.

Priority Queue (Min Heap): The most critical data structure used in Huffman coding is a priority queue, often implemented as a min-heap. The heap allows efficient extraction of the minimum element, which is essential for constructing the Huffman tree. The characters are initially inserted into the heap with their frequencies as keys, and nodes are repeatedly extracted and merged to build the tree.
