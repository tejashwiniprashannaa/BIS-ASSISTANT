@"
# BIS Standards Assistant

AI-Powered RAG Engine for Indian Standards and Government Procurement

## Overview

BIS Standards Assistant is an AI-assisted procurement standards analysis system designed to help users identify relevant Bureau of Indian Standards (BIS) standards from tender requirements.

The system uses Retrieval-Augmented Generation (RAG) to retrieve relevant BIS standards from a curated knowledge base and uses a local LLM to generate grounded explanations.

## Key Features

- Tender requirement analysis
- AI-assisted BIS standard retrieval
- Semantic search using vector embeddings
- RAG-based explanations
- Certification requirement information
- QCO and CRS metadata
- AI-detected related standards
- Structured procurement requirement extraction
- Officer review workflow
- SHA-256 hash-chain audit trail
- Audit integrity verification
- PDF report generation

## System Architecture

```text
Tender / Procurement Requirement
              |
              v
     Requirement Analysis
              |
              v
      Sentence Transformers
       (Embeddings)
              |
              v
          ChromaDB
     Semantic Retrieval
              |
              v
     Relevant BIS Standards
              |
              v
    Certification Metadata
              |
              v
       Local LLM (Ollama)
              |
              v
      Grounded Explanation
              |
              v
        Officer Review
              |
              v
        Audit Trail
       SHA-256 Hash Chain




## Screenshots

### 1. Dashboard
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/e516b86b-692b-4709-ab12-2bdd5088906d" />


### 2. Tender Input
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/70bb466d-be73-4749-baed-51ebb1b13cc1" />


### 3. AI-Generated Explanation
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/3da91c7b-25d4-47e8-b5ec-c4d0134aaf13" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/df8ec4c7-7061-42d6-8044-e539fbec2ae5" />


### 4. Officer Review
<img width="1600" height="772" alt="image" src="https://github.com/user-attachments/assets/e4282c10-47c4-46c6-aefc-2992676cd829" />

### 5. Standards PDF Bundle
<img width="1600" height="769" alt="image" src="https://github.com/user-attachments/assets/1c75b26b-32bd-441f-93ce-bffc580a8f71" />


### 6. Audit-Chain Verification
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/31e8f727-5404-405f-89ce-93be27d5eee4" />
