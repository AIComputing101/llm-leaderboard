# EXAONE-3.5

> Large Language Model

**Organization:** [LG](../../labs/lg.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

EXAONE-3.5 is a large language model developed by LG.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 32.0B
- **Training Tokens:** 6500.0B
- **Token:Param Ratio:** 204:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 78.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 39.7 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

“EXAONE”=“EXpert AI for EveryONE”. Training tokens/ratio dropped from EXAONE-3 7.8B with 8T (Aug/2024) to this (Dec/2024) 7.8B with 9T to 32B with 6.5T.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/LGAI-EXAONE/exaone-35-674d0e1bb3dcd2ab6f39dbb4)
- 📄 [Technical Documentation](https://arxiv.org/abs/2412.04862)

## 🔍 Related Models

**From LG:**
- See all models in [LG profile](../../labs/lg.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All LG Models](../../labs/lg.md)
