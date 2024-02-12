**Test repository**

Contains test ci/cd yml file, as well as ideal folder structure with some template files. 

Test project: Chatbot

Framework: Langchain

Model: Mistral7b, from huggingface (best to get one that is already quantized)

Backend: FastAPI or Ollama for endpoint, pgvector db (for RAG and memory purposes)

Frontend: Streamlit or chainlit

Other future features: RAG

Deployment: docker (don't need Celery and Rabbitmq for now)
