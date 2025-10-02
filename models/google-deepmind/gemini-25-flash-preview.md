# Gemini 2.5 Flash Preview

> Reasoning

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Gemini 2.5 Flash Preview is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 80.0B
- **Training Tokens:** 20000.0B
- **Token:Param Ratio:** 250:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 4.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 78.3 | Graduate-level reasoning |
| **HLE** | 12.1 | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Context in=1M, out=64k. Knowledge cutoff Jan/2025. Codename 'nebula'. Note: Gemini outputs are watermarked. I do not use GDM models.

## 🔗 Resources

- 🎮 [Try the Model](https://aistudio.google.com/prompts/new_chat?model=gemini-2.5-flash-preview-04-17)
- 📄 [Technical Documentation](https://deepmind.google/technologies/gemini/flash/)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
