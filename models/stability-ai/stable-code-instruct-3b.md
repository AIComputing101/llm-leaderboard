# Stable Code Instruct 3B

> Large Language Model

**Organization:** [Stability AI](../../labs/stability-ai.md)
**Released:** Mar/2024
**Access:** 🟢 Public

---

## 📊 Overview

Stable Code Instruct 3B is a large language model developed by Stability AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 2.7B
- **Training Tokens:** 560.0B
- **Token:Param Ratio:** 208:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.1 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** code, The Stack

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

Context window=16,384. Trained on The Stack dataset.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/stabilityai/stable-code-instruct-3b)
- 📄 [Technical Documentation](https://stability.ai/news/introducing-stable-code-instruct-3b)

## 🔍 Related Models

**From Stability AI:**
- See all models in [Stability AI profile](../../labs/stability-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Stability AI Models](../../labs/stability-ai.md)
