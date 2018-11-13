# Information-Retrieval
Team project for IR course

Topic : Efficient Vector Space Retrieval
Efficient IR system needs to be able to retrieve results, in real-time, from very large document collections

The goal is to implement the Vector Space Model model with all „tricks” for efficient retrieval

Task:
1. Implement a tiered index, with the configurable number of tiers
2. Implement pre-clustering of documents in the collection using randomly chosen leaders (i.e., vectors in the same space as document vectors)
3. Transformation of TF-IDF VSM document vectors into the lower-dimensional vector space via random projections
4. Evaluate different variants in terms of  (1) retrieval performance (e.g., MAP),  (2) retrieval speed

Datasets: Medical Information Retrieval dataset: https://tinyurl.com/nfcorpus
