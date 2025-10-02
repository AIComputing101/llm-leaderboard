# Hermes 4

> Reasoning

**Organization:** [Nous Research](../../labs/nous-research.md)
**Released:** Aug/2025
**Access:** 🟢 Public

---

## 📊 Overview

Hermes 4 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 405.0B
- **Training Tokens:** 15656.0B
- **Token:Param Ratio:** 39:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.4 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 87.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | 80.5 | Advanced MMLU variant |
| **GPQA** | 70.5 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Based on Llama 3. Announce: https://hermes4.nousresearch.com/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/NousResearch/Hermes-4-405B-FP8)
- 📄 [Technical Documentation](https://arxiv.org/abs/2508.18255)

## 🔍 Related Models

**From Nous Research:**
- See all models in [Nous Research profile](../../labs/nous-research.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Nous Research Models](../../labs/nous-research.md)
