# Llama 4 Behemoth

> SOTA

**Organization:** [Meta AI](../../labs/meta-ai.md)
**Released:** Apr/2025
**Access:** 🔴 Private

---

## 📊 Overview

Llama 4 Behemoth represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 2000.0B
- **Training Tokens:** 30000.0B
- **Token:Param Ratio:** 15:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 25.8 (Extremely powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 82.2 | Advanced MMLU variant |
| **GPQA** | 73.7 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

2T-A288B. Announced Apr/2025, abandoned Jul/2025. "We also trained a teacher model, Llama 4 Behemoth, that outperforms GPT-4.5, Claude Sonnet 3.7, and Gemini 2.0 Pro on STEM-focused benchmarks such as MATH-500 and GPQA Diamond... 288B active parameters, 16 experts, and nearly two trillion total parameters."

## 🔗 Resources

- 🎮 [Try the Model](Abandoned)
- 📄 [Technical Documentation](https://ai.meta.com/blog/llama-4-multimodal-intelligence/)

## 🔍 Related Models

**From Meta AI:**
- See all models in [Meta AI profile](../../labs/meta-ai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Meta AI Models](../../labs/meta-ai.md)
