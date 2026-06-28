# Month 1 – Week 3: AI Knowledge Assistant Prototype

- **Goal:** Build the core retrieval-augmented generation (RAG) pipeline.  
- **Daily Tasks:**  
  - **Day 1:** *Document Ingestion* – Write scripts to load and preprocess knowledge data (e.g. text files or PDFs). Chunk long documents into manageable pieces.  
  - **Day 2:** *Embeddings & Indexing* – Generate embeddings (with OpenAI or HuggingFace models) for each chunk. Index them in a vector DB or in-memory structure.  
    - *Note:* Vector DBs (like Pinecone) manage embeddings efficiently.  
  - **Day 3:** *Retrieval* – Implement a retrieval function: given a user query, embed it and find top-K most similar document chunks (cosine similarity search).  
  - **Day 4:** *LLM Q&A (RAG)* – Send the retrieved context to the LLM along with the user’s question to generate an answer. For example, use a prompt like “Given this context, answer the question…”.  
    - *Resources:* Hugging Face on RAG – RAG “fetches relevant passages and conditions generation on them”, making answers more factual.  
  - **Day 5:** *API Endpoint* – Add a FastAPI route `/ask` that accepts a question, runs the RAG pipeline, and returns the answer JSON. Test end-to-end (user query ⇒ LLM answer).  
  - **Day 6:** *Refinement & Testing* – Improve reliability: handle empty results, add caching, log queries. Write unit tests for the core RAG function.  
  - **Day 7:** *Review* – Demo the full flow. Gather feedback. Update PRD with any new requirements discovered (e.g. scale, multi-user support).  
- **Deliverables:** Working prototype of the AI Knowledge Assistant (query→answer). Drafted Product Requirements Document (PRD).
