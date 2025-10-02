# Z-Code++

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Aug/2022
**Access:** 🔴 Private

---

## 📊 Overview

Z-Code++ is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.71B
- **Training Tokens:** 500.0B
- **Token:Param Ratio:** 705:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
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

abstractive text summarization, 710M, outperforms PaLM 540B. "Due to the limited computational resource, Z-Code++LARGE is trained with only 500B tokens instead of 1T tokens as that for mT5 training."

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2208.09770v1)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
