# Gemma 3n

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** May/2025
**Access:** 🟢 Public

---

## 📊 Overview

Gemma 3n is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MatFormer
- **Parameters:** 4.0B
- **Training Tokens:** 8000.0B
- **Token:Param Ratio:** 2,000:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 62.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Matryoshka Transformer or MatFormer model architecture. 850M (696M / 620M / 582M).

## 🔗 Resources

- 🎮 [Try the Model](https://ai.google.dev/gemma/docs/gemma-3n)
- 📄 [Technical Documentation](https://developers.googleblog.com/en/introducing-gemma-3n/)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MatFormer models](../../architectures/matformer.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
