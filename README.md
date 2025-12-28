# Assistente Virtual Inteligente (RAG + Streamlit)

Este é um chatbot avançado desenvolvido para responder a dúvidas com base em documentos internos específicos. Ao contrário de modelos de IA genéricos, este assistente utiliza a técnica **RAG (Retrieval-Augmented Generation)** para consultar uma base de conhecimento privada antes de gerar uma resposta, garantindo precisão e evitando alucinações.

---

##  Demonstração

Aqui você pode ver o assistente em ação:

<p align="center">
  <img src="https://github.com/user-attachments/assets/a43af4c0-2ea1-4d23-881c-451c285b489e" alt="Demonstração do Chatbot" width="800px">
</p>



---

###  Funcionalidades
* **Interface Web:** Interface amigável e responsiva construída com **Streamlit**.
* **Consulta de Documentos:** O assistente lê e interpreta documentos internos para fornecer respostas contextualizadas.
* **Baixa Latência:** Integrado com a API da **Groq**, permitindo respostas extremamente rápidas.
* **Arquitetura RAG:** Utiliza LangChain para orquestrar a recuperação de dados e a geração de texto.

###  Stack Tecnológica
* **Interface:** [Streamlit](https://streamlit.io/)
* **Orquestração de LLM:** [LangChain](https://www.langchain.com/)
* **Modelo de Linguagem:** Llama 3.3 70B (via Groq Cloud)
* **Linguagem de Programação:** Python 3.12

---
