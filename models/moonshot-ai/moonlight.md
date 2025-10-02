# Moonlight

> Large Language Model

**Organization:** [Moonshot AI](../../labs/moonshot-ai.md)
**Released:** Feb/2025
**Access:** 🟢 Public

---

## 📊 Overview

Moonlight is a large language model developed by Moonshot AI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 16.0B
- **Training Tokens:** 5700.0B
- **Token:Param Ratio:** 357:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.0 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 70.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | 42.4 | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"Scaling law experiments indicate that Muon achieves ∼ 2× computational efficiency compared to AdamW with compute optimal training." https://github.com/MoonshotAI/Moonlight?tab=readme-ov-file

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/moonshotai/Moonlight-16B-A3B)
- 📄 [Technical Documentation](https://github.com/MoonshotAI/Moonlight/blob/master/Moonlight.pdf)

## 🔍 Related Models

**From Moonshot AI:**
- See all models in [Moonshot AI profile](../../labs/moonshot-ai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Moonshot AI Models](../../labs/moonshot-ai.md)
