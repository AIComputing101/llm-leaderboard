# TimesFM

> Large Language Model

**Organization:** [Google](../../labs/google.md)
**Released:** Feb/2024
**Access:** 🟢 Public

---

## 📊 Overview

TimesFM is a large language model developed by Google.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.2B
- **Training Tokens:** 100.0B
- **Token:Param Ratio:** 500:1 ✅ Compute-optimal

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

Time-series forecasting only. 'a large pretraining corpus of 100B real world time-points' may be more than 100B tokens.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/google/timesfm-release-66e4be5fdb56e960c1e482a6)
- 📄 [Technical Documentation](https://blog.research.google/2024/02/a-decoder-only-foundation-model-for.html)

## 🔍 Related Models

**From Google:**
- See all models in [Google profile](../../labs/google.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google Models](../../labs/google.md)
