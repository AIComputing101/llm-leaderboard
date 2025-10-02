# mixtral-8x22b

> Large Language Model

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

mixtral-8x22b is a large language model developed by Mistral.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 141.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 15:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 1.8 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 77.75 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MoE=22Bx8, seq=65536.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/mistral-community/Mixtral-8x22B-v0.1)
- 📄 [Technical Documentation](https://mistral.ai/news/mixtral-8x22b/)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
