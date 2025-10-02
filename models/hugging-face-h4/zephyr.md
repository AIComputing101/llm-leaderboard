# Zephyr

> Large Language Model

**Organization:** [Hugging Face H4](../../labs/hugging-face-h4.md)
**Released:** Oct/2023
**Access:** 🟢 Public

---

## 📊 Overview

Zephyr is a large language model developed by Hugging Face H4.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.3B
- **Training Tokens:** 800.0B
- **Token:Param Ratio:** 110:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.3 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 33.0 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Mistral with 'aligned' data removed from dataset

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/HuggingFaceH4/zephyr-7b-alpha)
- 📄 [Technical Documentation](https://huggingface.co/HuggingFaceH4/zephyr-7b-alpha)

## 🔍 Related Models

**From Hugging Face H4:**
- See all models in [Hugging Face H4 profile](../../labs/hugging-face-h4.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Hugging Face H4 Models](../../labs/hugging-face-h4.md)
