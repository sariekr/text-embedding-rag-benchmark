# Text Embedding RAG Benchmark

An early AIMultiple study of large embedding models for product-review retrieval. The project compares whether models find the source review for a question and measures the time needed to return results.

> [Read the open-source embedding benchmark on AIMultiple](https://aimultiple.com/open-source-embedding-models)

## Original project scope

The comparison covers Llama Embed Nemotron 8B, GTE-Qwen2, SFR-Embedding-Mistral, E5-Mistral and GritLM.

- Amazon product reviews indexed in Qdrant.
- A shared set of questions and reference reviews.
- Top-1, Top-3 and Top-5 retrieval scores, plus query latency.
- Local inference on an NVIDIA A100 with INT8 quantization.

Retrieval scores describe where a reference review appears in the search results. Answer generation requires a separate evaluation.

## Published research

The linked article now covers a different model roster and multiple document domains. Its dataset, metrics and hosted inference setup differ from this earlier project.

Results from the earlier review-retrieval study are omitted here to keep the two evaluations distinct.

## Ownership

The benchmark implementation was developed for AIMultiple and belongs to AIMultiple. This repository contains a documentation summary. Source code and benchmark datasets are not distributed here.
