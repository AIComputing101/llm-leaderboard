# YOCO

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** May/2024
**Access:** 🟢 Public

---

## 📊 Overview

YOCO is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.0B
- **Training Tokens:** 1600.0B
- **Token:Param Ratio:** 534:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
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

With Tsingua. You Only Cache Once (YOCO). Long context "1M context length with near-perfect needle retrieval accuracy"

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/microsoft/unilm/tree/master/YOCO)
- 📄 [Technical Documentation](https://arxiv.org/abs/2405.05254)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
