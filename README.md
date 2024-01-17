# Langchain RAG Tutorial

Install dependencies.

```python
pip3 install -r requirements.txt
```

Create the Chroma DB.

```python
python create_database.py
```

Query the Chroma DB.

```python
python query_data.py "How does Alice meet the Mad Hatter?"
```

You'll also need to set up an OpenAI account (and set the OpenAI key in your environment variable) for this to work.

# Custom AI Assistant

Add ASSISTANT_ID in the .env file

install dependencies

```pip3 install openai```

run:

```python3 custom_ai_assistant.py```