# DeepSeek Local Chat - GUI

A local AI chat application using DeepSeek with a sleek PyQt5 GUI.

## Requirements

- Python 3.10+
- [Ollama](https://ollama.com/) installed and model downloaded

## Installation

1. Install the DeepSeek model via Ollama:

```bash
ollama pull deepseek-r1:8b
```
---


```deepseek_model_simple_chat.ipynb``` and ```deekseek_model_chat_rememberance.ipynb``` are working files with SIMPLE gui. 

Model I've used in these files is: 

- deepseek-r1:8b


# multiple_models_with_gui.ipynb

- Better gui and functionalities 
- I've used these open source models:
  
```bash
ollama run deepseek-r1:8b
ollama run deepseek-coder:6.7b	
ollama run deepseek-coder-v2:16b
ollama run llama3.1:8b
ollama run qwen2.5:14b
ollama run codellama:13b
ollama pull gpt-oss:20b
ollama pull qwen3-coder:30b
```

- There is a dropdown where we can select model of our choice, and response will be generated accordingly.

- Simple, user friendly GUI

