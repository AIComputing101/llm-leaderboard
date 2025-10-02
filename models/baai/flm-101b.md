# FLM-101B

> Large Language Model

**Organization:** [BAAI](../../labs/baai.md)
**Released:** Sep/2023
**Access:** 🟢 Public

---

## 📊 Overview

FLM-101B is a large language model developed by BAAI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 101.0B
- **Training Tokens:** 245.0B
- **Token:Param Ratio:** 3:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Train for $100k compute budget (on a cluster of 24 DGX-A800 GPU 8×80G servers for 21 days)

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/CofeAI/FLM-101B)
- 📄 [Technical Documentation](https://arxiv.org/abs/2309.03852)

## 🔍 Related Models

**From BAAI:**
- See all models in [BAAI profile](../../labs/baai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All BAAI Models](../../labs/baai.md)
