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


Q. what is the different between langchain and langgraph ? 

Core Architecture & Flow

• LangChain: Uses a linear, step-by-step sequential workflow where the output of one step feeds directly into the next (using pipeline or chain syntax like chain1 | chain2). Best suited for straightforward pipelines.
• LangGraph: Uses a graph-based state machine architecture built with nodes (actions) and edges (transitions). It explicitly supports non-linear flows, loops, cycles, and branching paths.

State & Memory Management

• LangChain: Implements implicit or limited state management, mainly tracking basic chat history or passing context sequentially without persistent multi-turn states across complex branches.
• LangGraph: Features explicit, persistent state management and built-in checkpoints. This allows applications to pause, wait for human-in-the-loop review, and resume right where they left off.

Use Cases & Complexity

• LangChain: Ideal for simple chatbots, single-agent tasks, document retrieval (RAG), text summarization, and quick prototyping. It offers 600+ out-of-the-box integrations for connecting to APIs and vector databases.
• LangGraph: Built for complex multi-agent systems, dynamic AI pipelines, conditional logic, and long-running or real-time interactive tasks.

How They Work Together

• They are not mutually exclusive; they belong to the same ecosystem. In fact, newer versions of LangChain use LangGraph under the hood for agent execution. You can use LangChain for modular tool integrations and LangGraph to orchestrate the heavy multi-agent workflow.

Q. What is dependency injection ? 

Dependency injection (DI) in Python is a design pattern where an object receives its dependencies from an external source rather than creating them itself. This technique promotes loose coupling, simplified unit testing, and highly modular code


Q. 
Quick Comparison


Feature	                  One-Shot Prompting	                                                              Few-Shot Prompting
Number of Examples	        1 example                                                                  	2 to 10 examples (commonly 3–5)
Task Complexity	              Simple tasks, formatting, basic style	                                    Complex, nuanced, or custom tasks
Accuracy	                    Good for basic alignment	                                                Higher consistency and precision
Token Usage	                  Economical / Low	                                                        Higher (uses more of the context window)
Preparation Time	            Fast (write one example)	                                                Moderate to high (craft multiple diverse examples)


Q. what is prompt engineering? 

Prompt engineering is the art and science of designing, structuring, and refining text instructions (prompts) to guide artificial intelligence models—especially large language models (LLMs) like ChatGPT or Claude—toward generating accurate, relevant, and useful outputs.

