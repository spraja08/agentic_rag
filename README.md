# agentic_rag

### Introduction
This is a self-correcting RAG pattern that checks the retrieved contexts for relevancy and the generated answers for hallucinations.\
It is loosely based on this Self-RAG [paper](https://arxiv.org/abs/2310.11511)\
<img title="flow"  src="resource/flow.png">\
The LLM used in this is llama3:8b. The embedding model used is mxbai-embed-large (dim is 1024).\
Both are ran locally using ollama:\
    a) Install ollama\
    b) Pull llama3 and mxbai-embed-large (ollama pull...)\
    Run the agentic_rag_index notebook before running the agentic_rag_generate notebook to create the vectorstore and index.
~
~
