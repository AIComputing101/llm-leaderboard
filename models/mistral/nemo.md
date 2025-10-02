# NeMo

> Large Language Model

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

NeMo is a large language model developed by Mistral.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 12.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 167:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 68.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

With NVIDIA. "Drop-in replacement of Mistral 7B". "trained using Megatron-LM, part of NVIDIA NeMo, with 3,072 H100 80GB Tensor Core GPUs" https://blogs.nvidia.com/blog/mistral-nvidia-ai-model/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/mistralai/Mistral-Nemo-Base-2407)
- 📄 [Technical Documentation](https://mistral.ai/news/mistral-nemo/)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
