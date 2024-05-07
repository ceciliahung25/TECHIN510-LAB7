## Key Learnings

### 1. Understanding Sentence Embeddings
- Learned how to generate sentence embeddings using the `sentence_transformers` library, which translates text into a high-dimensional space.
- Applied these embeddings to calculate the cosine similarity between sentences to understand their semantic similarities.

### 2. Implementing Semantic Search
- Explored semantic search capabilities by matching queries to documents based on semantic content.
- Used `semantic_search` function from `sentence_transformers.util` to find the most relevant documents for specific queries.

### 3. Tokenizer Usage and Tokenization
- Gained practical experience with tokenization using the `PreTrainedTokenizerFast` from the `transformers` library.
- Managed tokenization processes, converting text to tokens, and handled texts by splitting them into chunks that conform to token limits.

### 4. Handling Different Models and Libraries
- Experimented with different models for embedding generation, such as changing from specific models to `all-MiniLM-L6-v2`, observing impacts on performance.
- Addressed library-specific issues and errors, like compatibility warnings between different tokenizer classes.

### 5. Practical Application of NLP Concepts
- Applied NLP concepts to practical scenarios, such as modifying functions to manage large texts by breaking them into manageable chunks.
- Ensured these modifications did not exceed the models' maximum token input sizes.

### 6. Error Handling and Debugging
- Encountered and managed errors related to model mismatches and unexpected tokenizer behavior.
- Developed skills essential for creating robust NLP applications through debugging and error resolution.