# GPT-1

> SOTA

**Organization:** [OpenAI](../../labs/openai.md)
**Released:** Jun/2018
**Access:** 🟢 Public

---

## 📊 Overview

GPT-1 represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 0.117B
- **Training Tokens:** 98.4B
- **Token:Param Ratio:** 842:1 ✅ Compute-optimal

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

"GPT-1 — 984 M tokens corpus × 100 epochs × 1 token per word → 98.4 B tokens processed" Books only. "We train for 100 epochs on minibatches of 64 randomly sampled, contiguous sequences of 512 tokens." =3,276,800

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/openai-community/openai-gpt)
- 📄 [Technical Documentation](https://openai.com/blog/language-unsupervised/)

## 🔍 Related Models

**From OpenAI:**
- See all models in [OpenAI profile](../../labs/openai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenAI Models](../../labs/openai.md)
