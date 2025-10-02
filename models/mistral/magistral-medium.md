# Magistral Medium

> Reasoning

**Organization:** [Mistral](../../labs/mistral.md)
**Released:** Jun/2025
**Access:** 🟢 Public

---

## 📊 Overview

Magistral Medium is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 50.0B
- **Training Tokens:** 12000.0B
- **Token:Param Ratio:** 240:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.6 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 70.8 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Magistral Small=24B. Announce: https://mistral.ai/news/magistral

## 🔗 Resources

- 🎮 [Try the Model](https://chat.mistral.ai/chat)
- 📄 [Technical Documentation](https://mistral.ai/static/research/magistral.pdf)

## 🔍 Related Models

**From Mistral:**
- See all models in [Mistral profile](../../labs/mistral.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Mistral Models](../../labs/mistral.md)
