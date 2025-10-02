# Gemini 1.5 Flash

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** May/2024
**Access:** 🟢 Public

---

## 📊 Overview

Gemini 1.5 Flash is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 8.0B
- **Training Tokens:** 10000.0B
- **Token:Param Ratio:** 1,250:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.9 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 78.9 | General knowledge across 57 subjects |
| **MMLU-Pro** | 59.1 | Advanced MMLU variant |
| **GPQA** | 39.5 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

1M context length. Note: Gemini outputs are watermarked. I do not use GDM models.

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
