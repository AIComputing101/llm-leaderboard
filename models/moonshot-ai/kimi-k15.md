# Kimi k1.5

> Reasoning

**Organization:** [Moonshot AI](../../labs/moonshot-ai.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

Kimi k1.5 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 500.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 30:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 9.1 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 87.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 51.5 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"our system achieves state-of-the-art reasoning performance across multiple benchmarks and modalities---e.g., 77.5 on AIME, 96.2 on MATH 500, 94-th percentile on Codeforces, 74.9 on MathVista---matching OpenAI's o1". GPQA score is my estimate from pp13–14, noting that "the scores above come from an internal long-cot model with much smaller model size than k1.5 long-CoT model."

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/MoonshotAI/kimi-k1.5?tab=readme-ov-file)
- 📄 [Technical Documentation](https://arxiv.org/abs/2501.12599)

## 🔍 Related Models

**From Moonshot AI:**
- See all models in [Moonshot AI profile](../../labs/moonshot-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Moonshot AI Models](../../labs/moonshot-ai.md)
