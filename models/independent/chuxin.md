# ChuXin

> Large Language Model

**Organization:** [Independent](../../labs/independent.md)
**Released:** May/2024
**Access:** 🟢 Public

---

## 📊 Overview

ChuXin is a large language model developed by Independent.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.6B
- **Training Tokens:** 2300.0B
- **Token:Param Ratio:** 1,438:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 41.07 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"results on the ”Needle In A Haystack”(NIAH) tests indicate that ChuXin-1M performs well across all context window lengths up to 1M."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/chuxin-llm/Chuxin-1.6B-Base)
- 📄 [Technical Documentation](https://arxiv.org/abs/2405.04828)

## 🔍 Related Models

**From Independent:**
- See all models in [Independent profile](../../labs/independent.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Independent Models](../../labs/independent.md)
