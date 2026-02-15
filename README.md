# Awesome LLMOps [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, frameworks, platforms, and resources for Large Language Model Operations (LLMOps) — enabling production-ready, scalable, and reliable LLM applications.

LLMOps is the emerging practice of managing the lifecycle of large language models, including fine-tuning, deployment, monitoring, evaluation, versioning, and observability — similar to MLOps but optimized for LLMs and generative AI systems.

## Contents

- [Overview & Learning](#overview--learning)
- [Model Training & Fine-Tuning](#model-training--fine-tuning)
- [Evaluation & Benchmarking](#evaluation--benchmarking)
- [Serving & Inference](#serving--inference)
- [Monitoring & Observability](#monitoring--observability)
- [Prompt Engineering & Management](#prompt-engineering--management)
- [Data Management](#data-management)
- [Security & Safety](#security--safety)
- [Platforms & Frameworks](#platforms--frameworks)
- [Tooling Ecosystem](#tooling-ecosystem)
- [Related Awesome Lists](#related-awesome-lists)

## Overview & Learning

- **[LLMOps Guide (Weights & Biases)](https://wandb.ai/site/articles/llmops-the-new-mlops)** – High-level overview of LLMOps concepts and tools.
- **[LLMOps Field Guide (Fiddler)](https://www.fiddler.ai/blog/llmops-a-field-guide)** – A breakdown of the infrastructure stack for LLMOps.
- **[LangChain Cookbook](https://github.com/hwchase17/langchain-cookbook)** – Recipes for building with LangChain and LLMs.
- **[Full Stack Deep Learning](https://fullstackdeeplearning.com/)** – Practical LLM lifecycle, from training to deployment.

## Model Training & Fine-Tuning

- **[Hugging Face Transformers](https://github.com/huggingface/transformers)** – Leading library for pre-trained and fine-tunable LLMs.
- **[PEFT](https://github.com/huggingface/peft)** – Parameter-Efficient Fine-Tuning methods for LLMs.
- **[LoRA](https://arxiv.org/abs/2106.09685)** – Lightweight fine-tuning strategy for large models.
- **[Colossal-AI](https://github.com/hpcaitech/ColossalAI)** – Framework for efficient distributed LLM training.

## Evaluation & Benchmarking

- **[Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)** – Benchmarking open LLMs.
- **[Helm](https://crfm.stanford.edu/helm/latest/)** – Stanford’s framework for evaluating LLMs across tasks.
- **[LM Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness)** – Test harness for LLM evaluation.
- **[TruLens](https://github.com/truera/trulens)** – LLM observability and feedback tracking.

## Serving & Inference

- **[vLLM](https://github.com/vllm-project/vllm)** – Fast and memory-efficient inference for LLMs with continuous batching.
- **[TGI (Text Generation Inference)](https://github.com/huggingface/text-generation-inference)** – High-performance inference server by Hugging Face.
- **[DeepSpeed MII](https://github.com/microsoft/DeepSpeed-MII)** – Low-latency inference for Hugging Face models.
- **[Ray Serve](https://docs.ray.io/en/latest/serve/)** – Scalable model serving via Ray.

## Monitoring & Observability

- **[PromptLayer](https://www.promptlayer.com/)** – Log, monitor, and manage prompts across LLM providers.
- **[Arize AI](https://arize.com/)** – LLM monitoring, evaluation, and prompt tracing.
- **[Opik](https://github.com/comet-ml/opik)** – Open-source LLM observability, evaluation, and tracing platform.
- **[WhyLabs](https://whylabs.ai/)** – Observability for ML and LLM deployments.
- **[TruLens](https://trulens.org/)** – Feedback loop framework for evaluating and improving LLM apps.

## Prompt Engineering & Management

- **[LangChain](https://www.langchain.com/)** – Modular framework for chaining LLM calls and prompts.
- **[Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)** – Structured guide to writing effective prompts.
- **[PromptFoo](https://github.com/promptfoo/promptfoo)** – Compare, test, and evaluate LLM prompts easily.
- **[Guidance](https://github.com/microsoft/guidance)** – Prompt programming with structured control over model output.

## Data Management

- **[Label Studio](https://github.com/heartexlabs/label-studio)** – Open-source data labeling for fine-tuning and RAG pipelines.
- **[Weaviate](https://weaviate.io/)** – Vector database for semantic search and hybrid retrieval.
- **[Pinecone](https://www.pinecone.io/)** – Managed vector DB for similarity search and retrieval-augmented generation.
- **[ChromaDB](https://www.trychroma.com/)** – Open-source embeddings DB built for LLMs.

## Security & Safety

- **[Guardrails AI](https://github.com/shreya-sharma/guardrails)** – Validating and controlling LLM outputs.
- **[Rebuff](https://github.com/sail-sg/Rebuff)** – Open-source framework for prompt injection defense.
- **[Giskard](https://github.com/Giskard-AI/giskard)** – Testing, debugging, and securing LLM applications.
- **[OpenAI Moderation API](https://platform.openai.com/docs/guides/moderation)** – API for detecting harmful or unsafe content.

## Platforms & Frameworks

- **[LangChain](https://github.com/hwchase17/langchain)** – Infrastructure to build end-to-end LLM-powered apps.
- **[LLamaIndex](https://github.com/jerryjliu/llama_index)** – Connect data sources to LLMs via indexing.
- **[RAGStack (Haystack)](https://haystack.deepset.ai/)** – Retrieval-augmented generation framework.
- **[FastChat](https://github.com/lm-sys/FastChat)** – Open platform for serving and fine-tuning chat LLMs.

## Tooling Ecosystem

- **[Weights & Biases](https://wandb.ai/)** – Track and visualize model training and performance.
- **[MLflow](https://mlflow.org/)** – Platform for managing the ML lifecycle.
- **[PromptLayer](https://github.com/promptlayer/promptlayer-python)** – Middleware for logging and versioning prompt inputs and outputs.
- **[OpenLLM](https://github.com/bentoml/OpenLLM)** – Open-source platform to deploy and manage LLMs in production.

## Related Awesome Lists

- **[Awesome Prompt Engineering](https://github.com/awesomelistsio/awesome-prompt-engineering)**
- **[Awesome Generative AI](https://github.com/awesomelistsio/awesome-generative-ai)**
- **[Awesome ChatGPT](https://github.com/awesomelistsio/awesome-chatgpt)**
- **[Awesome MLOps](https://github.com/awesomelistsio/awesome-mlops)**

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
