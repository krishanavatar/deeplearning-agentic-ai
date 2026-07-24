# Agentic AI — DeepLearning.AI

Course repo for [Agentic AI](https://learn.deeplearning.ai/courses/agentic-ai) by Andrew Ng.

## Structure

```
.
├── notebooks/        # Lesson notebooks (downloaded from the course)
├── labs/             # Ungraded lab work
├── projects/         # Course projects
├── requirements.txt
└── .env.example
```

## Local Setup

### 1. Clone

```bash
git clone https://github.com/krishanavatar/deeplearning-agentic-ai.git
cd deeplearning-agentic-ai
```

### 2. Create a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set API keys

```bash
cp .env.example .env
# Edit .env and add your keys
```

### 5. Launch Jupyter

```bash
jupyter lab
```

## API Keys

The course uses various LLM providers. Add your keys to `.env`:

| Variable | Provider |
|---|---|
| `OPENAI_API_KEY` | OpenAI |
| `ANTHROPIC_API_KEY` | Anthropic (Claude) |
| `TAVILY_API_KEY` | Tavily (web search) |

Get keys from:
- https://platform.openai.com/api-keys
- https://console.anthropic.com/
- https://app.tavily.com/

## Course Link

https://learn.deeplearning.ai/courses/agentic-ai
