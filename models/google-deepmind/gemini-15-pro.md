# Gemini 1.5 Pro

> SOTA

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Feb/2024
**Access:** 🟢 Public

---

## 📊 Overview

Gemini 1.5 Pro represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 200.0B
- **Training Tokens:** 30000.0B
- **Token:Param Ratio:** 150:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.2 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 85.9 | General knowledge across 57 subjects |
| **MMLU-Pro** | 69.0 | Advanced MMLU variant |
| **GPQA** | 46.2 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Sparse MoE. Context window=1M and 10M for research. Note: Gemini outputs are watermarked. I do not use GDM models.

## 🔗 Resources

- 🎮 [Try the Model](https://aistudio.google.com/app/prompts/new_chat)
- 📄 [Technical Documentation](https://goo.gle/GeminiV1-5)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
