## Hi there, I'm Gabriel 👋

You can grab my full résumé on my [website](https://galinslp.github.io/galinslp/). But since we are on GitHub, I thought I’d let the command line do the talking:

```bash
user@MacBook ~ % cat gabriel.json
{
  "Gabriel": {
    "Role": "Data Scientist",
    "Current": {
      "Company": "Human Brains",
      "Focus": "Building production-ready AI agents and automated systems for multimodal data"
    },
    "Previously": [
      {
        "2023-2024": "Visiting Researcher @ Oregon State University"
      },
      {
        "2020-2025": "PhD in Computer Science @ Federal University of São Paulo"
      },
      {
        "2018-2020": "MSc in Applied Computing @ INPE"
      }
    ],
    "Principles": [
      "Start simple, scale smart",
      "Make it reproducible (docs, tests, pipelines)"
    ],
    "Environment": {
      "OS": ["macOS", "Ubuntu LTS"],
      "Shell": "zsh",
      "Editor": "Sublime Text",
      "LabNotebook": "Jupyter"
    }
  }
}

user@MacBook ~ % ./analyze_stack.py --input gabriel.json --verbose
[INFO] Loading trajectory...
[INFO] Resolving toolchain...
[SUCCESS] Expertise Loaded:

> Languages:      Python, SQL, JavaScript, C#, Julia, Scala
> ML / DL:        PyTorch, PyTorch Geometric, Hugging Face, TensorFlow, Keras
> GenAI Systems:  RAG, LangChain, LangGraph, embeddings, prompt engineering
> Data:           PostgreSQL, Snowflake, Neo4j
> Engineering:    Docker, AWS, FastAPI, Git

user@MacBook ~ % open https://galinslp.github.io/galinslp/
[INFO] Opening curriculum vitae...
```
