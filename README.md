# ETL and NLP Experiments

This repository contains a collection of Jupyter notebooks that demonstrate various natural language processing (NLP) techniques and an ETL (Extract, Transform, Load) process on a dataset of French painters. The notebooks showcase the usage of popular libraries such as Hugging Face Transformers, NLTK, and Newspaper3k to perform tasks like text summarization, text generation, and evaluation of summaries using popular metrics.

## Table of Contents

1. [Text Summarization with PEGASUS-XSUM](#text-summarization-with-pegasus-xsum)
2. [Text Summarization Evaluation using BLEU, METEOR, and ROUGE Scores](#text-summarization-evaluation-using-bleu-meteor-and-rouge-scores)
3. [Text Generation using GPT-2](#text-generation-using-gpt-2)
4. [ETL on French Painters](#etl-on-french-painters)

## Text Summarization with PEGASUS-XSUM

This notebook demonstrates the process of summarizing text using the Google PEGASUS-XSUM model from the Hugging Face Transformers library. The PEGASUS-XSUM model is a pre-trained abstractive text summarization model that can generate concise summaries of long text inputs.

The notebook covers the following topics:

- Installation and importing libraries
- Fetching article content
- Checking GPU availability
- Splitting text into chunks
- Summarizing text
- Evaluating the summary

[Link to the notebook](https://github.com/louispaulet/ETL_tests/blob/master/summarization_experiment_2_google_pegasus_xsum.ipynb)

## Text Summarization Evaluation using BLEU, METEOR, and ROUGE Scores

This notebook demonstrates the process of summarizing a given text using the Hugging Face Transformers library and evaluating the generated summary using three popular evaluation metrics: BLEU, METEOR, and ROUGE scores.

The notebook covers the following topics:

- Installation and importing libraries
- Loading the summarization pipeline
- Generating a summary
- Defining evaluation metrics
- Testing evaluation functions
- Summarize and evaluate

[Link to the notebook](https://github.com/louispaulet/ETL_tests/blob/master/simple_summarization_pipeline_evaluation.ipynb)

## Text Generation using GPT-2

This notebook demonstrates the process of generating text using the GPT-2 model from the Hugging Face Transformers library. GPT-2 is a powerful language model capable of generating human-like text based on a given input prompt.

The notebook covers the following topics:

- Installation and importing libraries
- Checking GPU availability
- Loading model and tokenizer
- Defining text generation function
- Generating text

[Link to the notebook](https://github.com/louispaulet/ETL_tests/blob/master/gpt2_generation.ipynb)

## ETL on French Painters

This notebook demonstrates an ETL (Extract, Transform, Load) process on a dataset of French painters. The goal is to fetch data on French painters and their best artwork from the Wikidata SPARQL endpoint, process the data, and save it to a CSV file.

The notebook covers the following topics:

- Fetching French painters data
- Transforming the data
- Saving the data to a CSV file

[Link to the notebook](https://github.com/louispaulet/ETL_tests/blob/master/ETL_on_french_painters.ipynb)
