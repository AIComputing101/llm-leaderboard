# Transformer (big)

> SOTA

**Organization:** [Google](../../labs/google.md)
**Released:** Jun/2017
**Access:** 🟢 Public

---

## 📊 Overview

Transformer (big) represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.213B
- **Training Tokens:** 9.8B
- **Token:Param Ratio:** 47:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.0
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** books

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

"Transformer Big — 32 768 tokens per step × 300 000 steps → 9.83 B tokens processed" "We trained on the standard WMT 2014 English-German dataset consisting of about 4.5 million sentence pairs... For English-French, we used the significantly larger WMT 2014 English-French dataset consisting of 36M sentences and split tokens into a 32000 word-piece vocabulary. Sentence pairs were batched together by approximate sequence length. Each training batch contained a set of sentence pairs containing approximately 25000 source tokens and 25000 target tokens."

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/tensorflow/tensor2tensor?tab=readme-ov-file#walkthrough)
- 📄 [Technical Documentation](https://arxiv.org/abs/1706.03762)

## 🔍 Related Models

**From Google:**
- See all models in [Google profile](../../labs/google.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google Models](../../labs/google.md)
