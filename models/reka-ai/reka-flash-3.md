# Reka Flash 3

> Reasoning

**Organization:** [Reka AI](../../labs/reka-ai.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

Reka Flash 3 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 21.0B
- **Training Tokens:** 5000.0B
- **Token:Param Ratio:** 239:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.1 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 65.0 | Advanced MMLU variant |
| **GPQA** | 61.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"performs competitively with proprietary models such as OpenAI o1-mini, making it a good foundation to build applications that require low latency or on-device deployment. It is currently the best open model in its size category."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/RekaAI/reka-flash-3)
- 📄 [Technical Documentation](https://www.reka.ai/news/introducing-reka-flash)

## 🔍 Related Models

**From Reka AI:**
- See all models in [Reka AI profile](../../labs/reka-ai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Reka AI Models](../../labs/reka-ai.md)
