# Compression-Techniques
Implememtaion & comparison of compression techniques in Information Retrievel.

## Dataset Used:
Cranfield collections dataset, it consists of consists of 1400 documents.

## Methods
Areas for Compression in IR Systems:
1. Index Compression
2. Vector Representation Compression
3. Binarization/Quantization/Pruning for LTR Models

Scope of this project : Index and Vector Representation Compression

We have implemented following compression techniques:
Index Compression : 
	1.Dictionary Compression
	2. Postings compression

Embedding Compression:
	1. PCA Dimensionality Reduction
	2. Product Quantization
	
## To Replicate the Results
To run index_compression.ipynb simply run through the code.

To run Word_Embedding_Compression.ipynb follow below steps:
Step 1 : Copy the files crawl-300d-50K.vec and questions-words-trimmed in the 
same directory as the ipynb.
Step 2 : Change the paths in cell block 2 to local paths pointing to the two mentioned
files above. 
Step 3 : Run cells block by block.

Parameters can be changed for the product quantization and PCA dim reduction
in their corresponding cells.
