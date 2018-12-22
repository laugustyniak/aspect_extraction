# Aspect Extraction Experiments using sequence tagging -> LSTM-based approaches

## Installation 

Firstly, install INTEL's NLP Architect https://github.com/NervanaSystems/nlp-architect

Then run `aspect_extraction_experiments` with proper arguments. The most important will be to proveide path to all embedding's files. 

```bash
python aspect_extraction_experiments.py --embeddings-path /path/to/embeddings --models-path /path/where/models/will/be/stored/models --logs-path /path/where/logs/will/be/stored/logs-models
```