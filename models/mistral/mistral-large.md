# Mistral Large

> SOTA

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Feb/2024
**Access:** 🟢 Public

---

## 📊 Overview

Mistral Large represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 300.0B
- **Training Tokens:** 8000.0B
- **Token:Param Ratio:** 27:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 5.2 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 81.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

MMLU=81.2 (same as Flan-PaLM 2 340B, higher than PaLM 2 340B MMLU=78.3), 32k context window. API only (not open source).

## 🔗 Resources

- 🎮 [Try the Model](https://poe.com/Mistral-Large)
- 📄 [Technical Documentation](https://mistral.ai/news/mistral-large/)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
