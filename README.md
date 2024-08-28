# Huffman-Coding
Implementation of Huffman coding to compress and decompress text files.

-The algorithm works by first determining all of the file’s unique characters and their frequencies. 
-The characters and frequencies are then added to a Min-heap. 
-It then extracts two minimum frequency characters and adds them as nodes to a dummy root. 
-The value of this dummy root is the combined frequency of its nodes and this root node is added back to the Min-heap. 
-The procedure is then repeated until there is only one element left in the Min-heap. 

This way, a Huffman tree for a particular text file can be created.


