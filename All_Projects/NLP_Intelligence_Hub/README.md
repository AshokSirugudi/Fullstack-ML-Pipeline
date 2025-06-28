# NLP Intelligence Hub

A condensed, end-to-end NLP pipeline project that ingests unstructured text from multiple sources and intelligently routes it to appropriate NLP models for insight generation.

## 🎯 Purpose

- Centralize and demonstrate full-stack NLP engineering
- Auto-detect, route, and process various input formats (APIs, logs, databases, feedback)
- Output structured insight (sentiment, topics, intents, summaries)

## 🧠 Scope

- Not replication, but a personalized architecture showing:
  - Multi-source ingestion (web, DB, logs)
  - Smart preprocessing
  - Auto-model routing
  - Model execution + output formatting
  - Built with extensibility toward LLMs in mind

## 📁 Structure

- data_sources/
- ingestion/
- preprocessing/
- model_routing/
- nlp_models/
    - sentiment/
    - topic_modeling/
    - ner/
    - text_classification/
    - intent_detection/
    - summarization/
- outputs/
- pipeline_runner/
