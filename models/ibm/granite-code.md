# Granite Code

> Large Language Model

**Organization:** [IBM](../../labs/ibm.md)
**Released:** May/2024
**Access:** 🟢 Public

---

## 📊 Overview

Granite Code is a large language model developed by IBM.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 34.0B
- **Training Tokens:** 3500.0B
- **Token:Param Ratio:** 103:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.1 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** code

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 50.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MMLU=50 for 8B model only. Dataset: publicly available datasets (e.g., GitHub Code Clean, Starcoder data), public code repositories, and issues from GitHub.

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/ibm-granite/granite-code-models)
- 📄 [Technical Documentation](https://github.com/ibm-granite/granite-code-models/blob/main/paper.pdf)

## 🔍 Related Models

**From IBM:**
- See all models in [IBM profile](../../labs/ibm.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All IBM Models](../../labs/ibm.md)
