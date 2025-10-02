# OPT-175B

> Large Language Model

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** May/2022
**Access:** 🟢 Public

---

## 📊 Overview

OPT-175B is a large language model developed by Meta AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 175.0B
- **Training Tokens:** 300.0B
- **Token:Param Ratio:** 2:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 0.8 (Lightweight)
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

Only 30B available (Jun/2022)

## 🔗 Resources

- 🎮 [Try the Model](HF (train/deploy))
- 📄 [Technical Documentation](https://arxiv.org/abs/2205.01068)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
