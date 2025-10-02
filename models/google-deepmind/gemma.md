# Gemma

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Feb/2024
**Access:** 🟢 Public

---

## 📊 Overview

Gemma is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 6000.0B
- **Token:Param Ratio:** 858:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.7 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 64.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | 33.7 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

MMLU=64.3 (Llama 2 70B=68.9, ChatGPT 20B=70). Text only. Probably dense. Largest trained dataset (6T) besides frontier models.

## 🔗 Resources

- 🎮 [Try the Model](https://labs.pplx.ai/)
- 📄 [Technical Documentation](https://storage.googleapis.com/deepmind-media/gemma/gemma-report.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
