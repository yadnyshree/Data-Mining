The Colab shows the implementation of the various Approxiamate Nearest Neighbour Algorithms 

1. LSH

2. Exhaustive search

3. Product Quantization

4. Trees and Graphs

5. HNSW

All the above algorithms are implemented used faiss library.

The exact search for L2 is performed   

LSH : In LSH it is performed using the IndexLSH() function.<br>
Exhaustive search : In Exhaustive search it is performed using IndexFlatL2()<br>
Product Quantization : IndexIVFPQ().<br>
Trees and Graph : we install the annoy library.<br>
HNSW: IndexHNSWFlat().<br>
