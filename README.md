# Advanced-Retrieval-for-AI-with-Chroma

Chroma is one of the most popular open source vector databases. 

RAG, or retrieval augmented generation, retrieves relevant documents to give a large language model (LLM) access to information that wasn’t in its training set. But basic RAG also has common pitfalls: queries frequently return semantically similar results but don’t answer the question posed, or they may return irrelevant material which can distract the large language model (LLM) from the correct results. 

We will tackle these issues and learn to improve the relevancy of retrieved results with advanced techniques such as:

- **Query Expansion:** Expanding user queries improves information retrieval by including related concepts and keywords. Using an LLM makes this technique even more effective. 
- **Cross-encoder reranking:** Reranking retrieval results to select the results most relevant to your query improves your results.
- **Training and Utilizing Embedding Adapters:** Adding an adapter layer to reshape embeddings can improve retrieval by emphasizing elements relevant to your application. 
