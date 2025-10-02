# Gemini 2.0 Pro

> Large Language Model

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Feb/2025
**Access:** 🟢 Public

---

## 📊 Overview

Gemini 2.0 Pro is a large language model developed by Google DeepMind.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 200.0B
- **Training Tokens:** 20000.0B
- **Token:Param Ratio:** 100:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 6.7 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 79.1 | Advanced MMLU variant |
| **GPQA** | 64.7 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Context=2M. Disappointing benchmarks, this is the 'pro' (medium) not 'ultra' (large) model. Note: Gemini outputs are watermarked. I do not use GDM models.

## 🔗 Resources

- 🎮 [Try the Model](https://aistudio.google.com/prompts/new_chat?model=gemini-2.0-pro-exp-02-05)
- 📄 [Technical Documentation](https://blog.google/technology/google-deepmind/gemini-model-updates-february-2025/)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
