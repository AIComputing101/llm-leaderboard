# Codestral Mamba

> Large Language Model

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

Codestral Mamba is a large language model developed by Mistral.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 286:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
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

"Unlike Transformer models, Mamba models offer the advantage of linear time inference and the theoretical ability to model sequences of infinite length."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/mistralai/mamba-codestral-7B-v0.1)
- 📄 [Technical Documentation](https://mistral.ai/news/codestral-mamba/)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
