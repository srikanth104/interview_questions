# interview_questions

Q. What is the difference between FastAPI/ Flask/ Django?

Choosing between FastAPI, Flask, and Django comes down to architectural scale and concurrency requirements. FastAPI is an async-native framework optimized for high-performance APIs and AI services; Django is a monolithic, "batteries-included" ecosystem for complex web products; and Flask is a minimal, lightweight microframework focused on total developer flexibility.

Q. What is the tokenization? 
Tokenization is the process of breaking raw text into smaller pieces called tokens and converting each piece into a unique numerical ID that a large language model (LLM) can process

Q. what is the context windows? 
A context window is the maximum amount of text—measured in tokens (words, parts of words, or punctuation)—that a large language model (LLM) can process, hold, and reference during a single interaction.

Q. what is the different between put and patch? 
The primary difference between PUT and PATCH lies in how they update a resource. PUT replaces the entire resource with the new payload, while PATCH applies a partial modification, changing only the specific fields you provide

Q. what is cosine similarity? 
https://www.geeksforgeeks.org/dbms/cosine-similarity/

Q. what is a RAG ? 

Q. 
Keyword Search (Lexical Search)
• How it works: It matches the exact words or phrases you type against an index of documents. If a document contains those exact terms, it shows up. It relies on inverted indexes and direct string/token matching.

Semantic Search
How it works: It uses Artificial Intelligence (AI), Natural Language Processing (NLP), and vector embeddings (turning text into mathematical representations in a high-dimensional space). It compares the meaning of the query to the meaning of the documents.

Q. what is attention? 

Attention in Large Language Models (LLMs) is a mathematical mechanism that allows a model to focus on specific parts of a text when processing or generating a word, exactly like how a human pays attention to context clues when reading a sentence.

Q. What is Idempotency in the Context of REST APIs
In REST APIs, idempotence means that repeating the same request has the same effect as making it once, leaving the server in the same state. This makes API operations safe to retry without causing unintended changes.

It is especially important in distributed systems, where network failures or timeouts may require clients to resend requests. HTTP defines idempotency to ensure retries do not create duplicate operations or data inconsistencies. For example, if a profile update request times out, it can be safely retried without creating multiple records.

Q. Difference between Deep Learning and Machine Learning? 

https://www.geeksforgeeks.org/artificial-intelligence/difference-between-machine-learning-and-deep-learning/

