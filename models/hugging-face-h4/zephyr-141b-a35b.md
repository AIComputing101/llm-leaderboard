# Zephyr 141B-A35B

> Large Language Model

**Organization:** [Hugging Face H4](../../labs/hugging-face-h4.md)
**Released:** Apr/2024
**Access:** 🟢 Public

---

## 📊 Overview

Zephyr 141B-A35B is a large language model developed by Hugging Face H4.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 35.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 58:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.9 (Lightweight)
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

mixtral-8x22b finetune using Odds Ratio Preference Optimization (ORPO).

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/HuggingFaceH4/zephyr-orpo-141b-A35b-v0.1)
- 📄 [Technical Documentation](https://arxiv.org/abs/2403.07691)

## 🔍 Related Models

**From Hugging Face H4:**
- See all models in [Hugging Face H4 profile](../../labs/hugging-face-h4.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Hugging Face H4 Models](../../labs/hugging-face-h4.md)
