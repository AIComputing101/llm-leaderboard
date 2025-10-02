# DeepTransformers

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** May/2025
**Access:** 🔴 Private

---

## 📊 Overview

DeepTransformers is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 1.3B
- **Training Tokens:** 100.0B
- **Token:Param Ratio:** 77:1 ✅ Compute-optimal

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

"Atlas, a long-term memory module with high capacity that learns to memorize the context by optimizing the memory based on the current and past tokens, overcoming the online nature of long-term memory models. Building on this insight, we present a new family of Transformer-like architectures, called DeepTransformers, that are strict generalizations of the original Transformer architecture."

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2505.23735)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
