# Fippy

A file compression system based on the Huffman Coding algorithm, a greedy, lossless compression technique that builds an optimal prefix tree to encode characters efficiently based on their frequency.

The project provides two main functionalities:

-- Encode: Compresses a given text file into a Huffman-encoded format.
-- Decode: Reconstructs the original file from the compressed Huffman-coded file.

This implementation demonstrates practical applications of data structures such as priority queues (min-heaps), binary trees, and hash maps, along with algorithmic optimization techniques.

To run this project you need to create an executable file. 
You can follow the steps given below:

1) For compressing:

![Screenshot (1803)](https://user-images.githubusercontent.com/66181120/182021463-0c376291-4971-4351-ab9f-74b60a602d5f.png)

2) For Decompressing:

![Screenshot (1805)](https://user-images.githubusercontent.com/66181120/182021610-75978e56-6d41-44dc-8c42-9e8d3af8829e.png)



Example: inputFile.txt (2.07 MB) is compressed to compressedFile.huf (1.09 MB) file and decompressed back to ouputFile.txt (2.07 MB).

inputFile.txt

![Screenshot (1809)](https://user-images.githubusercontent.com/66181120/182021815-cb05bf61-aee4-4e98-a66e-b0f63fa3f3f9.png)

compressedFile.txt 

![Screenshot (1810)](https://user-images.githubusercontent.com/66181120/182021817-22dd8c34-9c18-48f9-a163-381b428e9aa3.png)

outputFile.txt

![Screenshot (1811)](https://user-images.githubusercontent.com/66181120/182021818-d51b68d8-44bc-44c0-b31c-ee502aa93a21.png)


![Screenshot (1814)](https://user-images.githubusercontent.com/66181120/182022046-948e75ef-1cb9-4741-8962-17e723ab817f.png)


Result: This project is just an implementation of Huffman coding, it is not as efficient as the compression algorithm used currently to compress files.
