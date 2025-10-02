# Llama-3.1-Nemotron-Ultra-253B

> Reasoning

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Llama-3.1-Nemotron-Ultra-253B is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 253.0B
- **Training Tokens:** 15600.0B
- **Token:Param Ratio:** 62:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 6.6 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 76.01 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Llama 3.1 405B base. "Llama-3.1-Nemotron-Ultra-253B-v1 is a large language model (LLM) which is a derivative of Meta Llama-3.1-405B-Instruct (AKA the reference model). It is a reasoning model that is post trained for reasoning, human chat preferences, and tasks, such as RAG and tool calling. The model supports a context length of 128K tokens. This model fits on a single 8xH100 node for inference."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/nvidia/Llama-3_1-Nemotron-Ultra-253B-v1)
- 📄 [Technical Documentation](https://developer.nvidia.com/blog/build-enterprise-ai-agents-with-advanced-open-nvidia-llama-nemotron-reasoning-models/)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
