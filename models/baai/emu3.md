# Emu3

> Large Language Model

**Organization:** [BAAI](../../labs/baai.md)
**Released:** Sep/2024
**Access:** 🟢 Public

---

## 📊 Overview

Emu3 is a large language model developed by BAAI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.0B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 125:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** special

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

VLM. Dataset estimates are based on the unrelated UW/Salesforce dataset MINT-1T (3.4B images, 927M documents) https://arxiv.org/abs/2406.11271v1

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/BAAI/Emu3-Gen)
- 📄 [Technical Documentation](https://arxiv.org/abs/2409.18869)

## 🔍 Related Models

**From BAAI:**
- See all models in [BAAI profile](../../labs/baai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All BAAI Models](../../labs/baai.md)
