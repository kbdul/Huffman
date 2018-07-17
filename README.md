# Image Compression using Huffman Coding
In 1952 David Huffman, a graduate student at Massachusetts Institute of Technology, developed an algorithm for lossless compression as part of his schoolwork. The algorithm is known as Huffman coding.
Huffman coding can be used to compress all sorts of data, which is an entropy-based algorithm relies on the frequency of symbols in an array.

## Algoritm of Huffman coding
The image compression techniques are categorized into two main classifications, ```Lossy compression``` techniques and ```Lossless compression``` techniques.

### Lossy Compression
 A technique in which the compressed image is
reconstructed with loss of data is called lossy compression.
The lossy compression technique has higher compression ratio, with loss of data in image.

### Lossless Compression
A technique in which the compressed image is
reconstructed without any loss of data is called lossless
compression. Lossless compression ratio are low, but gives high quality
of compressed image.

Huffman coding is lossless technique with more
attractive features in various application such as medical
survey, analysis, and technical drawing etc. Huffman coding
has better characteristics of image compression. 

|**```Block Diagram Flow```**|
|-----------------------------|
| Input image | 
|Split equal rows and coloumn|
Apply Huffman coding on individual rows and columns
Individual compressed image
sum of compressed individual image
Compressed image 
