# startup-validator
Created a startup idea validator that leverages NLP-based analysis to assess and score business ideas on factors like feasibility, market need, and innovation, helping early-stage founders refine their concepts.

# Startup Idea Validator

## **Overview**
This project is a web-based application that helps evaluate startup ideas using natural language processing and semantic search techniques. Users can input their idea, and the system retrieves and analyzes similar startup cases to provide structured insights on feasibility, problem clarity, market relevance, and overall viability.

---

## **Features**
1) Accepts startup ideas as free-text input  
2) Analyzes ideas using NLP techniques / semantic similarity search  
3) Provides structured feedback on:  
   - Problem clarity  
   - Market potential  
   - Feasibility  
   - Innovation level  
4) Simple and interactive web interface using Streamlit  
5) Real-time responses using backend embedding + FAISS search system  

---

## **Tech Stack**
1) Python  
2) Streamlit  
3) NLP techniques (Semantic Embedding using Sentence-BERT, FAISS similarity search)  
4) Pyngrok (for temporary live demo)  

---

## **How it works**
1) User enters a startup idea in the web interface  
2) Text is converted into embeddings using SentenceTransformer model  
3) The embedding is compared with existing startup dataset using FAISS  
4) Similar startups are retrieved based on cosine similarity  
5) System generates structured feedback based on nearest matches  
6) Results are displayed instantly on the Streamlit UI  

---

## **Note**
This project uses semantic search and embedding-based retrieval instead of traditional classification models, making it a lightweight AI-powered recommendation system.
