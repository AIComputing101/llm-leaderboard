# Phi-1

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Jun/2023
**Access:** 🔴 Private

---

## 📊 Overview

Phi-1 is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.3B
- **Training Tokens:** 51.0B
- **Token:Param Ratio:** 40:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.0
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

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

Code model. ‘breaking existing scaling laws by training a 1.3B-parameter model, which we call phi-1, for roughly 8 passes over 7B tokens (slightly over 50B total tokens seen) followed by finetuning on less than 200M tokens.’

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2306.11644)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
