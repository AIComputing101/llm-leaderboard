# Orca 2

> Large Language Model

**Organization:** [Microsoft](../../labs/microsoft.md)
**Released:** Nov/2023
**Access:** ❓ Unknown

---

## 📊 Overview

Orca 2 is a large language model developed by Microsoft.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 13.0B
- **Training Tokens:** 2001.0B
- **Token:Param Ratio:** 154:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.5 (Lightweight)
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

Llama 2 13B (2T) -> Orca 2 (GPT-4 finetune). Still an imitation model, overhyped: The False Promise of Imitating Proprietary LLMs https://arxiv.org/abs/2305.15717

## 🔗 Resources

- 📄 [Technical Documentation](https://arxiv.org/abs/2311.11045)

## 🔍 Related Models

**From Microsoft:**
- See all models in [Microsoft profile](../../labs/microsoft.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Microsoft Models](../../labs/microsoft.md)
