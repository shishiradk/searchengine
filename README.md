# searchengine

A Streamlit-powered conversational search assistant that leverages LangChain agents and multiple tools to answer user queries using web search, Wikipedia, and Arxiv.

## Features

- **Conversational Chatbot UI**: Built with Streamlit for interactive chat.
- **Multi-Source Search**: Integrates DuckDuckGo, Wikipedia, and Arxiv for comprehensive answers.
- **LangChain Agents**: Uses LangChain's agent framework to select the best tool for each query.
- **LLM Integration**: Supports Groq LLMs (e.g., Llama3-8b-8192, Qwen-Qwq-32b) via API key.
- **Customizable**: Easily add or modify tools and models.

## Installation

```sh
git clone https://github.com/yourusername/searchengine.git
cd searchengine
pip install -r requirements.txt
```

Create a `.env` file in the project root and add your Groq API key:
```
GROQ_API_KEY=your_groq_api_key_here
```

## Usage

```sh
streamlit run app.py
```

- Enter your Groq API key in the sidebar.
- Start chatting! Ask questions about general topics, scientific papers, or anything else.

## Project Structure

- `app.py` — Main Streamlit application.
- `requirements.txt` — Python dependencies.
- `tools_agents.ipynb` — Jupyter notebook for experimenting with LangChain tools and agents.
- `.env` — Environment variables (not included in version control).

## Example Queries

- "What is machine learning?"
- "Tell me about Langsmith."
- "What's the paper 1706.03762 about?"

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

Built with [LangChain](https://github.com/langchain-ai/langchain), [Streamlit](https://streamlit.io/), and
