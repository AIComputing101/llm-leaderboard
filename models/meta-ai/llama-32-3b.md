# Llama 3.2 3B

> Large Language Model

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** Sep/2024
**Access:** 🟢 Public

---

## 📊 Overview

Llama 3.2 3B is a large language model developed by Meta AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 3.21B
- **Training Tokens:** 9000.0B
- **Token:Param Ratio:** 2,804:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.6 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 63.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 32.8 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Text (LLM). "Pre-training. [For Llama 3.2 3B] We prune the models from their 8B siblings and use logits from the 8B and 70B models as token-level targets (token-level distillation). We then use knowledge distillation to recover performance."

## 🔗 Resources

- 🎮 [Try the Model](https://www.llama.com/)
- 📄 [Technical Documentation](https://www.llama.com/)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
