# Technical-Challenge

In this repository, I have built the technical approach for Career Copilot, an AI-driven career guidance tool. This project aims to provide users with highly personalized career guidance by matching user resumes with relevant job postings and offering insights based on labor market information (LMI). The solution leverages contextual embeddings using SentenceTransformers and retrieval-augmented generation (RAG) systems with Pinecone.

**TECHNICAL ARCHITECTURE** 📐✏️👷‍♀️: https://excalidraw.com/#json=d7QpT4f4pmgVJZf10TYe1,hF1Ka9mTwdT1o0vjANt1Zw

1. corpus_creation.ipynb :  Job postings are extracted from LinkedIn using BeautifulSoup
2. Career_Copilot_LLAMA2_RAG.ipynb 👨🏻‍💻: Semantic similarity and recommendation using Pinecone(RAG) and LLAMA 2 7b
3. requirements.txt : Package requirements for running the python notebook
