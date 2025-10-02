# Med-Flamingo

> Large Language Model

**Organization:** [Stanford](../../labs/stanford.md)
**Released:** Jul/2023
**Access:** 🟢 Public

---

## 📊 Overview

Med-Flamingo is a large language model developed by Stanford.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.3B
- **Training Tokens:** 1000.0B
- **Token:Param Ratio:** 121:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
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

Uses LAION OpenFlamingo 9B, based on LLaMA-7B text + 1.3B vision

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/snap-stanford/med-flamingo)
- 📄 [Technical Documentation](https://arxiv.org/abs/2307.15189)

## 🔍 Related Models

**From Stanford:**
- See all models in [Stanford profile](../../labs/stanford.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Stanford Models](../../labs/stanford.md)
