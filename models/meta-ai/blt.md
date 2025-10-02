# BLT

> Large Language Model

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

BLT is a large language model developed by Meta AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.0B
- **Training Tokens:** 4500.0B
- **Token:Param Ratio:** 563:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 57.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Byte Latent Transformer (BLT), a new byte-level LLM architecture that, for the first time, matches tokenization-based LLM performance

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/facebookresearch/blt)
- 📄 [Technical Documentation](https://ai.meta.com/research/publications/byte-latent-transformer-patches-scale-better-than-tokens/)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
