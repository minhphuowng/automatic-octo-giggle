README: Scalable Product Duplicate Detection with LSH
Project Overview

This project addresses the scalability issue in detecting duplicate product descriptions across various web shops. The goal is to develop a scalable solution using Locality Sensitive Hashing (LSH) for candidate pair generation and clustering methods to identify duplicates. This work builds upon prior research in duplicate detection but employs novel approaches for text representation and clustering.

Key features of the project include:

Candidate Pair Generation: Using LSH with shingled combined text representations rather than binary vectors to create scalable and effective candidate lists.
Clustering for Duplicate Detection: Leveraging sentence embedding-based dissimilarity matrices for hierarchical clustering instead of traditional q-grams or token-based similarity.
Evaluation Metrics: Pair quality, pair completeness, and F1*-measure are used to evaluate the performance of the proposed methodology.
The dataset used comprises 1,624 product descriptions from four web shops (Amazon, Newegg, Best Buy, and The Nerds), with products described through titles and key-value pairs.
