# Nemotron-H-56B-Base

> Reasoning

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Nemotron-H-56B-Base is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 56.0B
- **Training Tokens:** 20000.0B
- **Token:Param Ratio:** 358:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 84.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | 60.5 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

https://research.nvidia.com/labs/adlr/nemotronh/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/nvidia/Nemotron-H-56B-Base-8K)
- 📄 [Technical Documentation](https://arxiv.org/abs/2504.03624)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
