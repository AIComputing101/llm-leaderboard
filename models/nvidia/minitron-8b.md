# Minitron-8B

> Large Language Model

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

Minitron-8B is a large language model developed by NVIDIA.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 4.0B
- **Training Tokens:** 94.0B
- **Token:Param Ratio:** 24:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 63.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Pruned and distilled from Nemotron-4 15B: https://developer.nvidia.com/blog/how-to-prune-and-distill-llama-3-1-8b-to-an-nvidia-llama-3-1-minitron-4b-model/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/nvidia/Mistral-NeMo-Minitron-8B-Base)
- 📄 [Technical Documentation](https://blogs.nvidia.com/blog/mistral-nemo-minitron-8b-small-language-model/)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
