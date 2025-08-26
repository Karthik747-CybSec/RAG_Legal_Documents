# RAG_Legal_Documents
Processing legal documents using Retrieval-Augmented Generation (RAG).

This Python notebook analyzes a collection of legal and NDA documents by calculating similarity scores, extracting contract-related Q&A pairs, and demonstrating how to structure a dataset for legal document question answering tasks.

1. File Operations and Structure
   The notebook loads several legal document files (mostly NDAs and agreement templates) and organizes them for downstream processing.
   It displays a sample of the dataset by showing file names and their corresponding similarity matrices.

2. Document Similarity Analysis
   Pairwise similarity scores are calculated between different NDA and agreement documents, visualizing how closely files match in content or structure.

3. Separate similarity matrices are created for two document groups:
   NDA/Confidentiality Agreements
   Other Legal Agreements (Content License, Supply, Promotion, Transportation, Franchise, IP Agreements).

4. ContractNLI Dataset Extraction
   Key contract-related questions are extracted from the ContractNLI dataset embedded in the notebook.
   For each document, the notebook demonstrates how to select contextual spans that answer specific legal questions.
   This enables machine learning or rule-based systems to locate relevant information inside NDA/legal agreements.

5. Insights and Results
   Provides foundational workflows for similarity analysis, question extraction, and annotated answer extraction within legal documents.
   Sets the stage for automating legal QA tasks, facilitating dataset creation for contract comprehension models, and benchmarking similarity across varied legal agreements.
