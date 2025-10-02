# YuLan-Mini

> Large Language Model

**Organization:** [Renmin](../../labs/renmin.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

YuLan-Mini is a large language model developed by Renmin.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 2.4B
- **Training Tokens:** 1080.0B
- **Token:Param Ratio:** 450:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.2 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 51.79 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"1.08T tokens for training. Among them are 481B English web data, 138B general English knowledge, 227B code pre-training data, 16.7B code instruction data, 93.8B mathematics pre-training data, 15.5B mathematics instruction data, and 108B Chinese data."

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/RUC-GSAI/YuLan-Mini)
- 📄 [Technical Documentation](https://arxiv.org/abs/2412.17743)

## 🔍 Related Models

**From Renmin:**
- See all models in [Renmin profile](../../labs/renmin.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Renmin Models](../../labs/renmin.md)
