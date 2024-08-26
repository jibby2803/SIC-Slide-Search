# SIC-Slide-Search
Samsung Innovation Campus Capstone Project

## Introduction
This project aims to support students of the Samsung Innovation Campus in easily searching for knowledge within very lengthy slides. This is a project that applies RAG (Retrieval-Augmented Generation) with image data. I use the OpenCLIP model to embed images into vectors and utilize ChromaDB as the vector store.

<p align="center">
  <img src="./result/rag.png" width=800><br/>
  <i>Result</i>
</p>


## Result
<p align="center">
  <img src="./result/deo.gif" width=600><br/>
  <i>Result</i>
</p>

## How to use
You can apply this code for other slides or use cases by following the instruction below

* *Store your slides in **slides** directory*
* *Install libraries*
```bash
pip install -r requirements.txt
```
* *Process slides and create vectorstore*
```bash
python ingest.py
```
* *Run gradio interface*
```bash
python gradio_app.py
```

## Acknowledge
LangChain Templates: https://templates.langchain.com/