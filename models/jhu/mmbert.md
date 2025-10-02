# mmBERT

> Large Language Model

**Organization:** [JHU](../../labs/jhu.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

mmBERT is a large language model developed by JHU.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.307B
- **Training Tokens:** 3000.0B
- **Token:Param Ratio:** 9,772:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
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

"a modern multilingual encoder trained on 3T tokens and 1833 languages. We introduce several novel elements in training: an inverse masking schedule and a cascading annealed language learning schedule for multilingual data" Announce: https://huggingface.co/blog/mmbert

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/jhu-clsp/mmbert-a-modern-multilingual-encoder-68b725831d7c6e3acc435ed4)
- 📄 [Technical Documentation](https://arxiv.org/abs/2509.06888)

## 🔍 Related Models

**From JHU:**
- See all models in [JHU profile](../../labs/jhu.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All JHU Models](../../labs/jhu.md)
