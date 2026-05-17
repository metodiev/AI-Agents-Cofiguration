# AI-Agents-Cofiguration

The following repository will explain how to configure AI agents locally

## Configure Ollama

### Stack
- Ollama
- Continue.dev
- VS Code / Cursor
- qwen2.5-coder:14b

1. Installation:
Navigate to the official Ollama site and download the bin, for you OS

```bash
https://ollama.com/download/mac?utm_source=chatgpt.com
```

```
brew install ollama
```

To start Ollama

```
ollama serve
```

2. Download a coding model:

```bash
ollama pull qwen2.5-coder:14b
```

or 

```bash
ollama pull deepseek-coder-v2
```

3. Install coding agent:

Continue.dev


