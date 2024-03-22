**File Zipper (Greedy Huffman Encoder)**

**Overview**

This project involves developing a file zipper using the Greedy Huffman Encoder algorithm. The goal is to compress files by assigning variable-length binary codes to each character based on their frequency in the input file. This compression technique results in a significant reduction in file size without any loss of data.

**Methodology**

**Greedy Huffman Encoder:**

Implemented the Greedy Huffman Encoder algorithm for compression.
Constructed a Huffman tree based on the frequency of characters in the input file.
Assigned variable-length binary codes to each character, with shorter codes for more frequent characters.

**File Compression:**

Read the input file and encoded its content using the Huffman codes generated.
Compressed the file by replacing characters with their corresponding Huffman codes.

**File Decompression:**

Developed a file decompression algorithm to reverse the compression process.
Used the Huffman tree to decode the compressed binary data back into the original text.
Usage

**Dependencies:**

Python 3.x
No external libraries required.


**Results**

Achieved significant file size reduction without any loss of data.
Compression ratio: 0.43

Example

Compressed example.txt from 1 MB to 500 KB using the File Zipper.
