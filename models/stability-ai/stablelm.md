# StableLM

> Large Language Model

**Organization:** [Stability AI](../../labs/stability-ai.md)
**Released:** Apr/2023
**Access:** 🟢 Public

---

## 📊 Overview

StableLM is a large language model developed by Stability AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 65.0B
- **Training Tokens:** 1500.0B
- **Token:Param Ratio:** 24:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.0 (Mid-tier)
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

contains 1.5 trillion tokens, roughly 3x the size of The Pile. These models will be trained on up to 1.5 trillion tokens. The context length for these models is 4096 tokens.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/spaces/stabilityai/stablelm-tuned-alpha-chat)
- 📄 [Technical Documentation](https://github.com/stability-AI/stableLM/)

## 🔍 Related Models

**From Stability AI:**
- See all models in [Stability AI profile](../../labs/stability-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Stability AI Models](../../labs/stability-ai.md)
