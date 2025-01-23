# basics_of_Langchain

1. Load: This component handles the ingestion of data from various sources, such as PDFs, HTML files, and text documents. The implementation of data loading occurs in the data ingestion module.

2. Split: After loading the data, it is transformed by splitting it into manageable text chunks. Given that large language models (LLMs) have limitations regarding context size, this step is crucial for optimizing query performance and relevance.

3. Embed: In this step, the entire text is converted into vector representations. This embedding process enables efficient processing and analysis of the data.

4. Store: Finally, the vectors are stored in a Vector Database, such as FAISS, ChromaDB, or AstraDB. This allows for querying the stored data, where the results provide contextual information through similarity searches.
