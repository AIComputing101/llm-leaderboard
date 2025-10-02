# DeepHermes 3 Preview

> Reasoning

**Organization:** [Nous Research](../../labs/nous-research.md)
**Released:** Feb/2025
**Access:** 🟢 Public

---

## 📊 Overview

DeepHermes 3 Preview is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.0B
- **Training Tokens:** 15200.0B
- **Token:Param Ratio:** 1,900:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 38.0 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Based on Llama 3 8B. GPQA score based on GPT-4o's analysis of the chart :-/ "one of the first models in the world to unify Reasoning (long chains of thought that improve answer accuracy) and normal LLM response modes into one model." https://x.com/NousResearch/status/1890148004029759612

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/NousResearch/DeepHermes-3-Llama-3-8B-Preview)
- 📄 [Technical Documentation](https://huggingface.co/NousResearch/DeepHermes-3-Llama-3-8B-Preview)

## 🔍 Related Models

**From Nous Research:**
- See all models in [Nous Research profile](../../labs/nous-research.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Nous Research Models](../../labs/nous-research.md)
