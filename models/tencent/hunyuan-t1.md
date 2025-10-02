# Hunyuan T1

> Reasoning

**Organization:** [Tencent](../../labs/tencent.md)
**Released:** Feb/2025
**Access:** 🟢 Public

---

## 📊 Overview

Hunyuan T1 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 389.0B
- **Training Tokens:** 7000.0B
- **Token:Param Ratio:** 18:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 5.5 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 87.2 | Advanced MMLU variant |
| **GPQA** | 69.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"Based on Turbo S, by introducing technologies such as long thinking chains, retrieval enhancement and reinforcement learning, Hunyuan also launched the reasoning model T1 with deep thinking. This model has been fully launched on Tencent Yuanbao （ Tencent Hunyuan T1 model is open to all users ） , users can choose Deepseek R1 or Tencent Hunyuan T1 model to answer. The official version of Tencent Hunyuan T1 model will be launched soon, providing API access and other services to the outside world."

## 🔗 Resources

- 🎮 [Try the Model](https://cloud.tencent.com/apply/p/i2zophus2x8)
- 📄 [Technical Documentation](https://mp.weixin.qq.com/s/BwQkXpEitOm1Piz60SE-4A)

## 🔍 Related Models

**From Tencent:**
- See all models in [Tencent profile](../../labs/tencent.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tencent Models](../../labs/tencent.md)
