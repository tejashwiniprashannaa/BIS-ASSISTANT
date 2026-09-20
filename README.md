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


<img width="1600" height="772" alt="WhatsApp Image 2026-09-20 at 4 37 44 PM" src="https://github.com/user-attachments/assets/9f91ad53-c1ab-49fb-9a3b-a65fae20a699" />
<img width="1600" height="769" alt="WhatsApp Image 2026-09-20 at 4 36 16 PM" src="https://github.com/user-attachments/assets/7ae82e78-ecc5-4699-9869-7442ca9f1175" />
<img width="1600" height="899" alt="WhatsApp Image 2026-09-20 at 4 32 45 PM" src="https://github.com/user-attachments/assets/994a080e-9bf0-41ce-ad59-779d6123676e" />
<img width="1600" height="899" alt="WhatsApp Image 2026-09-20 at 4 31 27 PM" src="https://github.com/user-attachments/assets/52542964-9d47-43c4-b79e-c44fb16af660" />
<img width="1600" height="899" alt="WhatsApp Image 2026-09-20 at 4 30 41 PM" src="https://github.com/user-attachments/assets/f850a89b-be54-4576-8434-88ea1a4f6b0d" />
<img width="1600" height="900" alt="WhatsApp Image 2026-09-20 at 4 29 43 PM" src="https://github.com/user-attachments/assets/a72e5565-0e9b-4195-ae6c-8baca068259c" />
<img width="1600" height="899" alt="WhatsApp Image 2026-09-20 at 4 29 01 PM (1)" src="https://github.com/user-attachments/assets/288e5de6-2714-4411-854b-e18e697b8c91" />

