#  FastAPI Embedding Server with Sentence Transformers (Colab + Cloudflare Tunnel)

This project provides a **lightweight embedding server** using **FastAPI** and **Sentence Transformers**.  
It is designed to run in **Google Colab**, exposing the server to the internet via **Cloudflare Tunnel**.

---

##  Features
-  Embedding generation using **`sentence-transformers/all-mpnet-base-v2`**
-  FastAPI server with `/embed` endpoint
-  Public URL access via **Cloudflare Tunnel** (`trycloudflare.com`)
-  Easy integration with RAG pipelines or chatbot applications
-  Kill endpoint (`/kill`) to unassign the Colab runtime safely

