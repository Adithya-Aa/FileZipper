File Zipper using Huffman Coding

This project is a file compression and decompression utility built using the Huffman Coding Algorithm, a classic technique for lossless data compression. It efficiently reduces file sizes without losing any original content, especially suitable for text-based files.

Features

File Compression:
Compresses .txt files into a compact binary file (.bin) using Huffman coding.

File Decompression:
Restores a compressed file (.bin) back to its original .txt format.

Demo Compression Mode:
Generates a human-readable version of the compressed output to help visualize the encoding process.

File Types Used
Type Description
Input File Original file to be compressed (.txt)
Compressed File Binary file created after compression (.bin)
Demo Compressed File Text-based version of compressed data (.txt)
Decompressed File Output file after restoring the data (.txt)
Huffman Tree File Text file containing the generated Huffman tree
Usage Guide

Compile the Code:
Use any C++ compiler (e.g., g++ main.cpp -o FileZipper).

Run the Executable:

./FileZipper

Select an Operation:

1 → Compress a File

2 → Decompress a File

3 → Demo Compression

4 → Exit Program

Follow the Prompts:

Provide input/output filenames as requested.

Compressed files will be saved with .bin.

Decompressed files will be saved with .txt.

Requirements

A C++ compiler (e.g., GCC, Clang, or MSVC)

Uses only standard C++ libraries — no external dependencies

Contributor

Adithya
