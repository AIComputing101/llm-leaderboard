# DolphinGemma

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

DolphinGemma is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.4B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 5,000:1 ✅ Compute-optimal

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

"trained on Atlantic spotted dolphin sounds, we anticipate its potential utility for researchers studying other cetacean species, like bottlenose or spinner dolphins... Developed by Google, this AI model makes use of specific Google audio technologies: the SoundStream tokenizer efficiently represents dolphin sounds, which are then processed by a model architecture suited for complex sequences. This ~400M parameter model is optimally-sized to run directly on the Pixel phones WDP uses in the field."

## 🔗 Resources

- 🎮 [Try the Model](https://blog.google/technology/ai/dolphingemma/)
- 📄 [Technical Documentation](https://blog.google/technology/ai/dolphingemma/)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
