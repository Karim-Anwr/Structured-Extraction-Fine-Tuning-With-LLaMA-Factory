# News Structured Information Extraction & Fine-Tuning With LLaMA-Factory

## Overview

This project demonstrates **structured information extraction** from Arabic news stories using **LLMs** and **fine-tuning** with **LoRA** on Qwen2.5-1.5B-Instruct.  

The pipeline supports:

- Extracting structured data from raw Arabic news articles.
- Generating JSON outputs based on **Pydantic schemas**.
- Fine-tuning a large language model (LLM) for domain-specific structured extraction tasks.
- Optionally integrating **VLM** (Vision-Language Model) and **OCR** for document/image-based news.

---

## Installation

Clone the repository and install dependencies:

```bash
# Clone the repository
git clone --depth 1 https://github.com/hiyouga/LLaMA-Factory.git
cd LLaMA-Factory

# Install LLaMA-Factory
pip install -e .

# Install additional dependencies
pip install -qU transformers==4.48.3 datasets==3.2.0 optimum==1.24.0
pip install -qU openai==1.61.0 wandb
pip install -qU json-repair==0.29.1 faker==35.2.0
pip install -qU vllm==0.7.2
pip install -q huggingface_hub
"# Structured-Extraction-Fine-Tuning-With-LLaMA-Factory" 
"# Structured-Extraction-Fine-Tuning-With-LLaMA-Factory" 
"# Structured-Extraction-Fine-Tuning-With-LLaMA-Factory" 
