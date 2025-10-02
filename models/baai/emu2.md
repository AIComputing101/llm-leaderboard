# Emu2

> Large Language Model

**Organization:** [BAAI](../../labs/baai.md)
**Released:** Dec/2023
**Access:** 🟢 Public

---

## 📊 Overview

Emu2 is a large language model developed by BAAI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 37.0B
- **Training Tokens:** 4.0B
- **Token:Param Ratio:** 1:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.0
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

VLM. Gemini clone. Outperforms Flamingo 80B. The Pile for text, but only sampled 3.6B tokens (1.4% of the dataset).

## 🔗 Resources

- 🎮 [Try the Model](https://baaivision.github.io/emu2/)
- 📄 [Technical Documentation](https://arxiv.org/abs/2312.13286)

## 🔍 Related Models

**From BAAI:**
- See all models in [BAAI profile](../../labs/baai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All BAAI Models](../../labs/baai.md)
