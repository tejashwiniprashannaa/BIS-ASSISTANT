# BIS Standards Assistant
**Privacy-First RAG & Compliance Engine for Government Procurement**

> Eliminating tender compliance rejections by mapping complex procurement requirements to verified Bureau of Indian Standards (BIS), QCO, and CRS mandates—powered by a local LLM and secured with a tamper-proof SHA-256 audit trail.

---

## The Problem
Procurement officers and MSME vendors spend hours manually cross-referencing thousands of BIS standards, Quality Control Orders (QCOs), and Compulsory Registration Scheme (CRS) rules against tender documents. Missing a single mandatory standard leads to bid disqualification, legal delays, and compliance penalties.

## Why This Solution Stands Out
* **100% Air-Gapped Data Privacy:** Runs locally via **Ollama**, ensuring confidential government tender drafts never leave the internal network.
* **Tamper-Proof Accountability:** Every AI recommendation and officer approval is logged in a **SHA-256 hash-chain audit trail** with built-in integrity verification.
* **Actionable Compliance Metadata:** Goes beyond text search by surfacing mandatory QCO/CRS flags, related IS codes, and export-ready PDF compliance reports.

---

## System Architecture
```text
Tender Document / Requirement
       │
       ▼
Structured Requirement Extraction
       │
       ▼
Sentence Transformers (Embeddings) ──► ChromaDB (Vector Store)
       │
       ▼
Relevant BIS Standards + QCO/CRS Metadata
       │
       ▼
Local LLM (Ollama) ──► Grounded Compliance Explanation
       │
       ▼
Officer Review Workflow ──► SHA-256 Hash-Chain Audit Trail ──► PDF Report

## Screenshots



<img width="1000" alt="Dashboard" src="https://github.com/user-attachments/assets/9f91ad53-c1ab-49fb-9a3b-a65fae20a699" />
<img width="1000" alt="Audit-Chain Verification" src="https://github.com/user-attachments/assets/a72e5565-0e9b-4195-ae6c-8baca068259c" />


<img width="1000" alt="Additional Screenshot" src="https://github.com/user-attachments/assets/288e5de6-2714-4411-854b-e18e697b8c91" />



<img width="1000" alt="Tender Input" src="https://github.com/user-attachments/assets/7ae82e78-ecc5-4699-9869-7442ca9f1175" />





<img width="1000" alt="Officer Review" src="https://github.com/user-attachments/assets/52542964-9d47-43c4-b79e-c44fb16af660" />




<img width="1000" alt="Dashboard" src="https://github.com/user-attachments/assets/9f91ad53-c1ab-49fb-9a3b-a65fae20a699" />



<img width="1000" alt="Standards PDF Bundle" src="https://github.com/user-attachments/assets/f850a89b-be54-4576-8434-88ea1a4f6b0d" />



<img width="1000" alt="AI-Generated Explanation" src="https://github.com/user-attachments/assets/994a080e-9bf0-41ce-ad59-779d6123676e" />
