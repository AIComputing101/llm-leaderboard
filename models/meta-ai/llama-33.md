# Llama 3.3

> SOTA

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

Llama 3.3 represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 70.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 215:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.4 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 86.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | 68.9 | Advanced MMLU variant |
| **GPQA** | 50.5 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Drop-in replacement for Llama 3.1 70B, comparable performance to Llama 3.1 405B.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/meta-llama/Llama-3.3-70B-Instruct)
- 📄 [Technical Documentation](https://github.com/meta-llama/llama-models/blob/main/models/llama3_3/MODEL_CARD.md)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
