# Generative AI Projects
This repository explores the development of **Text-to-SQL** applications—systems that allow users to interact with relational databases using natural language.

## 📂 Repository Structure
The codebase is divided into two main strategies:

### 1. `with_Langchain`
* **Approach:** Utilizes LangChain's `SQLDatabase` utilities and `create_agent`.
* **Tech Stack:** LangChain, SQLAlchemy.

### 2. `without_langchain_agent`
* **Approach:** A "from scratch" implementation of Text-to-SQL logic.
* **Tech Stack:** Python, Direct LLM API calls using Gemini api sdk, SQLAlchemy.
