# FLAME

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Jan/2023
**Access:** 🔴 Private

---

## 📊 Overview

FLAME is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.06B
- **Training Tokens:** 9.0B
- **Token:Param Ratio:** 150:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.0
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

T5 for Excel formulas, very small 60M params, "We start from a dataset of 927M formulas" estimate 10x multiplier for 9B tokens

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2301.13779)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
