# 🤖 Sistema Multimodal com Agentic RAG e LLM Routing

Este projeto implementa uma aplicação web de Inteligência Artificial Generativa capaz de analisar imagens e responder perguntas utilizando modelos multimodais, combinando técnicas de RAG (Retrieval-Augmented Generation) e embeddings vetoriais.

---

## 🚀 Funcionalidades

- 📷 Upload de imagens (JPG, PNG)
- 💬 Perguntas baseadas na imagem
- 🧠 Análise multimodal com LLM (Google Gemini Vision)
- 🔎 Integração com base vetorial (FAISS)
- 📚 Uso de embeddings para recuperação de contexto
- ⚡ Interface interativa com Streamlit

---

## 🧠 Arquitetura

O sistema é composto por:

1. **Interface Web**
   - Streamlit para interação com o usuário

2. **Modelo Multimodal**
   - Google Gemini Vision para análise de imagens

3. **Camada de Embeddings**
   - HuggingFace (sentence-transformers)

4. **Banco Vetorial**
   - FAISS para busca semântica

5. **Pipeline**
   - Upload → Processamento → LLM → Resposta

---

## 🛠️ Tecnologias Utilizadas

- Python
- Streamlit
- LangChain
- Google Generative AI (Gemini)
- FAISS
- HuggingFace Embeddings


