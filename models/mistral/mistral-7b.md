# Mistral 7B

> Large Language Model

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Sep/2023
**Access:** 🟢 Public

---

## 📊 Overview

Mistral 7B is a large language model developed by Mistral.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.3B
- **Training Tokens:** 800.0B
- **Token:Param Ratio:** 110:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 30.9 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Apache 2.0, Sliding Window Attention (SWA) to handle longer sequences at smaller cost

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/mistralai)
- 📄 [Technical Documentation](https://mistral.ai/news/announcing-mistral-7b/)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
