# RAG PDF Q&A 

### Ollama setup
```
# Mac
https://ollama.com/download/Ollama-darwin.zip

# Ubuntu 20.04
curl -fsSL https://ollama.com/install.sh | sh

verify:
ollama
    this will run without any error
ollama run mistral
    this will show options without any error

ollama run mistral:instruct 
```

## Set up
```
python --verison
Python 3.11.7

pip install -r requirements.txt
```

### Test local
```
jupyter lab

verify:
http://0.0.0.0:
```

```
open pdf-qa.ipynb
```

To run Streamlit app:

```
Streamlit run streamlit-app.py
```