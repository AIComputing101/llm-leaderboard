# UltraLong-8B

> Large Language Model

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

UltraLong-8B is a large language model developed by NVIDIA.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 1,875:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 67.31 | General knowledge across 57 subjects |
| **MMLU-Pro** | 43.28 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Llama-3.1-8B-Instruct base. 4M context window.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/nvidia/Llama-3.1-8B-UltraLong-4M-Instruct)
- 📄 [Technical Documentation](https://arxiv.org/abs/2504.06214)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
