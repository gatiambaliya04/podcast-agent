# 🎙️ Podcast Agent using LangGraph

This project builds an autonomous podcast content generator using [LangGraph](https://github.com/langchain-ai/langgraph). It leverages LLM agents to search the web, synthesize content, and write podcast scripts, all structured in a graph-based flow.

---

## Features

- Autonomous research using tools like Web Search
- Memory and context passing between agents
- Script generation and summarization
- Iterative flow using LangGraph's edge logic

---

## Project Structure

```
generate_podcast_agent_langgraph.ipynb    # Main Jupyter notebook
README.md                                 # You're here
```

---

## Requirements

Install dependencies in a virtual environment:

```bash
pip install -r requirements.txt
```

If you don't have `requirements.txt`, here’s a starter:

```txt
langgraph
langchain
openai
python-dotenv
tiktoken
```

You may also need:
- `arxiv`, `serpapi`, or similar tools (depending on tools used in LangGraph)
- `IPython`, if running via notebook

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/podcast-agent-langgraph.git
cd podcast-agent-langgraph
```

2. Set your environment variables (in a `.env` file):

```env
OPENAI_API_KEY=your_openai_key
SERPAPI_API_KEY=your_serpapi_key
```

3. Open the notebook and run:

```bash
jupyter notebook generate_podcast_agent_langgraph.ipynb
```

4. Follow the prompts inside the notebook to generate podcast episodes!

---

## How It Works

LangGraph is used to create a directed graph of autonomous agents. The nodes represent tasks such as:

- Topic research
- Content planning
- Script generation
- Episode summarization

Edges define control flow logic, and the system loops or terminates based on outputs from the nodes.

---

## Sample Output

Coming soon! You can include screenshots of generated podcast scripts here.

---

## License

MIT License

---

## Acknowledgements

- [LangGraph](https://github.com/langchain-ai/langgraph)
- [LangChain](https://github.com/langchain-ai/langchain)
- OpenAI and SerpAPI for APIs

