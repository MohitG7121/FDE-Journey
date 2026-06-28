# Architecture Document

## Overview
*High-level description of system goals and context.*

## Components
- **Frontend:** (e.g. Streamlit app or Web UI)  
- **Backend:** FastAPI service handling requests.  
- **LLM Service:** OpenAI or local model for generation.  
- **Vector Database:** (e.g. Pinecone) for embeddings.  
- **Database:** (e.g. SQLite/Postgres) for any relational data.

## Data Flow
*Describe request flow:* user → backend → [vector DB → backend] → LLM → user.

## Diagrams
*Include system and component diagrams (e.g. see `assets/system_architecture.svg`).*

## Decisions
*Rationale for key choices (e.g. why FastAPI, why a vector DB, etc.).*
