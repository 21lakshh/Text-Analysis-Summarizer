# Text Analysis and Summarizer

## Overview
This project is a **Text Analysis and Summarization** tool that processes input text through a structured workflow to classify, extract key entities, and generate concise summaries. It is built using **LangChain** and **LangGraph** for AI-powered text processing.

## Features
- **Text Classification**: Categorizes input text into predefined categories (e.g., News, Blog, Research, or Other).
- **Entity Extraction**: Identifies and extracts key entities such as persons, organizations, and locations.
- **Text Summarization**: Generates a concise summary of the input text.

## Workflow
The system follows a structured workflow using LangGraph:
```python
workflow("classification_node", classification_node)
workflow("extract_entities", extract_entities)
workflow("summarize", summarize)
```

### Technologies Used
- **LangChain**: Enables conversational AI capabilities.
- **LangGraph**: Helps create a structured workflow for text analysis and summarization.
