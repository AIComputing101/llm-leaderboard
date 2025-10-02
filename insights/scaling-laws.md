# Scaling Laws Analysis

Analysis of parameter count vs training tokens across all models.

**Last Updated:** 2025-10-02

## Chinchilla Scaling Law

The Chinchilla paper suggests optimal ratio of **20:1** (tokens to parameters) for compute-optimal training.

### Models Exceeding Chinchilla Optimal (≥20:1)

**Count:** 440 models

| Model | Lab | Params | Tokens | Ratio | ALScore |
|-------|-----|--------|--------|-------|----------|
| [Sailor2](../models/sail/sailor2.md) | Sail | 20.0B | 18510.0B | 926:1 | 2.0 |
| [Apriel-5B](../models/servicenow/apriel-5b.md) | ServiceNow | 5.0B | 4500.0B | 900:1 | 0.5 |
| [phi-3.5-mini](../models/microsoft/phi-35-mini.md) | Microsoft | 3.8B | 3400.0B | 895:1 | 0.4 |
| [SEA-LIONv3](../models/ai-singapore/sea-lionv3.md) | AI Singapore | 9.24B | 8200.0B | 888:1 | 0.9 |
| [phi-3-mini](../models/microsoft/phi-3-mini.md) | Microsoft | 3.8B | 3300.0B | 869:1 | 0.4 |
| [Gemma](../models/google-deepmind/gemma.md) | Google DeepMind | 7.0B | 6000.0B | 858:1 | 0.7 |
| [Falcon Mamba 7B](../models/tii/falcon-mamba-7b.md) | TII | 7.0B | 6000.0B | 858:1 | 0.7 |
| [OLMoE-1B-7B](../models/allen-ai/olmoe-1b-7b.md) | Allen AI | 6.9B | 5900.0B | 856:1 | 0.7 |
| [GPT-1](../models/openai/gpt-1.md) | OpenAI | 0.117B | 98.4B | 842:1 | 0.0 |
| [RWKV-7 Goose](../models/rwkv/rwkv-7-goose.md) | RWKV | 0.4B | 332.0B | 830:1 | 0.0 |
| [DiffuCoder](../models/apple/diffucoder.md) | Apple | 7.0B | 5630.0B | 805:1 | 0.7 |
| [Ministral 8B](../models/mistral/ministral-8b.md) | Mistral | 8.0B | 6000.0B | 750:1 | 0.7 |
| [Phi-4-reasoning-plus](../models/microsoft/phi-4-reasoning-plus.md) | Microsoft | 14.0B | 10016.0B | 716:1 | 1.2 |
| [Phi-4](../models/microsoft/phi-4.md) | Microsoft | 14.0B | 10000.0B | 715:1 | 1.2 |
| [ERNIE-4.5-21B-A3B-Thinking](../models/baidu/ernie-45-21b-a3b-thinking.md) | Baidu | 21.0B | 15000.0B | 715:1 | 1.9 |
| [Z-Code++](../models/microsoft/z-code.md) | Microsoft | 0.71B | 500.0B | 705:1 | 0.1 |
| [Yi-Coder](../models/01-ai/yi-coder.md) | 01-ai | 9.0B | 6200.0B | 689:1 | 0.8 |
| [gpt-oss-20b](../models/openai/gpt-oss-20b.md) | OpenAI | 20.0B | 13000.0B | 650:1 | 1.7 |
| [o3-mini](../models/openai/o3-mini.md) | OpenAI | 20.0B | 13000.0B | 650:1 | 1.7 |
| [MAP-Neo](../models/international/map-neo.md) | International | 7.0B | 4500.0B | 643:1 | 0.6 |
| [Reka Edge](../models/reka-ai/reka-edge.md) | Reka AI | 7.0B | 4500.0B | 643:1 | 0.6 |
| [Maya](../models/cohere/maya.md) | Cohere | 8.0B | 4800.0B | 600:1 | 0.7 |
| [SmolLM2](../models/hugging-face/smollm2.md) | Hugging Face | 1.7B | 1000.0B | 589:1 | 0.1 |
| [SmolLM](../models/hugging-face/smollm.md) | Hugging Face | 1.7B | 1000.0B | 589:1 | 0.1 |
| [Teuken-7B](../models/opengpt-x/teuken-7b.md) | OpenGPT-X | 7.0B | 4000.0B | 572:1 | 0.6 |
| [Qwen3-Omni](../models/alibaba/qwen3-omni.md) | Alibaba | 30.0B | 17000.0B | 567:1 | 2.4 |
| [QwenLong-L1-32B](../models/alibaba/qwenlong-l1-32b.md) | Alibaba | 32.0B | 18000.0B | 563:1 | 2.5 |
| [K2-Think](../models/mbzuai/k2-think.md) | MBZUAI | 32.0B | 18000.0B | 563:1 | 2.5 |
| [INTELLECT-2](../models/prime-intellect/intellect-2.md) | Prime Intellect | 32.0B | 18000.0B | 563:1 | 2.5 |
| [s1-32B](../models/stanford/s1-32b.md) | Stanford | 32.0B | 18000.0B | 563:1 | 2.5 |


### Under-trained Models (<20:1)

Models trained with fewer tokens relative to their parameter count may have room for improvement through additional training.

**Count:** 140 models


---

[← Back to Home](../README.md)
