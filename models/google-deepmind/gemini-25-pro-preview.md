# Gemini 2.5 Pro Preview

> Reasoning, SOTA

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

Gemini 2.5 Pro Preview represents state-of-the-art performance in its category, with advanced reasoning capabilities.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 400.0B
- **Training Tokens:** 80000.0B
- **Token:Param Ratio:** 200:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 18.9 (Very powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 84.0 | Graduate-level reasoning |
| **HLE** | 18.8 | High-level evaluation |

**Analysis:** Outstanding reasoning performance on GPQA (>80%), approaching expert-level problem solving.

## 🏷️ Model Tags

`Reasoning`, `SOTA`

## 📝 Additional Notes

Context in=1M, out=64k. Knowledge cutoff Jan/2025. HLE SOTA. Codename 'nebula'. Note: Gemini outputs are watermarked. I do not use GDM models.

## 🔗 Resources

- 🎮 [Try the Model](https://aistudio.google.com/prompts/new_chat?model=gemini-2.0-pro-exp-02-05)
- 📄 [Technical Documentation](https://blog.google/technology/google-deepmind/gemini-model-thinking-updates-march-2025/#building-on-best-gemini)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
