# Kimi K2

> Reasoning, SOTA

**Organization:** [Moonshot AI](../../labs/moonshot-ai.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

Kimi K2 represents state-of-the-art performance in its category, with advanced reasoning capabilities.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 1000.0B
- **Training Tokens:** 15500.0B
- **Token:Param Ratio:** 16:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 13.1 (Very powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 89.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | 81.1 | Advanced MMLU variant |
| **GPQA** | 75.1 | Graduate-level reasoning |
| **HLE** | 4.7 | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`, `SOTA`

## 📝 Additional Notes

1TA32B. 1T parameters and 384 experts. Open source SOTA.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/moonshotai/Kimi-K2-Instruct)
- 📄 [Technical Documentation](https://moonshotai.github.io/Kimi-K2/)

## 🔍 Related Models

**From Moonshot AI:**
- See all models in [Moonshot AI profile](../../labs/moonshot-ai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Moonshot AI Models](../../labs/moonshot-ai.md)
