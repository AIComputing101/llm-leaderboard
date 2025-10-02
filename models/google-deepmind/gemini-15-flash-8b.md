# Gemini 1.5 Flash-8B

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Aug/2024
**Access:** 🟢 Public

---

## 📊 Overview

Gemini 1.5 Flash-8B is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.0B
- **Training Tokens:** 8000.0B
- **Token:Param Ratio:** 1,000:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.8 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 68.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 30.8 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Announce: https://x.com/OfficialLoganK/status/1828480085353234535 1M context for all modalities. Note: Gemini outputs are watermarked. I do not use GDM models.

## 🔗 Resources

- 🎮 [Try the Model](https://ai.google.dev/)
- 📄 [Technical Documentation](https://arxiv.org/abs/2403.05530)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
