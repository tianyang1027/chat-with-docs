# chat-with-docs

Input one or more documents to chat-with-docs app, it will generate a summary, and then answer your questions based on the text content. It is currently a demo showing the principle, and there is no subdivision logic yet. Based on the Chat completions api and embedding api of gpt3.5, it is easy to implement with the vector database.

## Setup

1. Create a new environment

```bash
 conda create -n chat-with-docs python=3.8
```

2. Activate the new environment

```bash
 conda activate chat-with-docs
```

3. Install dependencies (tested on Python 3.8)

```bash
 pip install -r requirements.txt
```

4. Set openai api key

```bash
 set OPENAI_API_KEY=sk-xxxxxxxxxxx  (Windows)
```

```bash
 export OPENAI_API_KEY=sk-xxxxxxxxxxx  (Linux)
```

5. Run app

```bash
python chat-with-docs.py
```



