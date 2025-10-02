# Gemini Robotics 1.5

> Reasoning

**Organization:** [Google DeepMind](../../labs/google-deepmind.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

Gemini Robotics 1.5 is designed for advanced reasoning and multi-step problem solving.

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
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 59.6 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

2. "vision-language-action (VLA) model turns visual information and instructions into motor commands for a robot to perform a task." Available to select partners.

## 🔗 Resources

- 📄 [Technical Documentation](https://storage.googleapis.com/deepmind-media/gemini-robotics/Gemini-Robotics-1-5-Tech-Report.pdf)

## 🔍 Related Models

**From Google DeepMind:**
- See all models in [Google DeepMind profile](../../labs/google-deepmind.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Google DeepMind Models](../../labs/google-deepmind.md)
