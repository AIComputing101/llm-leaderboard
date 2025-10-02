# Gemini Robotics-ER 1.5

> Reasoning

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

Gemini Robotics-ER 1.5 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 30.0B
- **Training Tokens:** 30000.0B
- **Token:Param Ratio:** 1,000:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.2 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 83.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Outstanding reasoning performance on GPQA (>80%), approaching expert-level problem solving.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

1. "vision-language model (VLM) reasons about the physical world, natively calls digital tools and creates detailed, multi-step plans to complete a mission." Available to all devs.

## 🔗 Resources

- 🎮 [Try the Model](https://aistudio.google.com/?model=gemini-robotics-er-1.5-preview)
- 📄 [Technical Documentation](https://storage.googleapis.com/deepmind-media/gemini-robotics/Gemini-Robotics-1-5-Tech-Report.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
