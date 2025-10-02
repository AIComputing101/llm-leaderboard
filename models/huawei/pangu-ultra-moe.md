# Pangu Ultra MoE

> Reasoning

**Organization:** [Huawei](../../labs/huawei.md)
**Released:** May/2025
**Access:** 🔴 Private

---

## 📊 Overview

Pangu Ultra MoE is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 718.0B
- **Training Tokens:** 13000.0B
- **Token:Param Ratio:** 19:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 10.2 (Very powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 91.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | 83.5 | Advanced MMLU variant |
| **GPQA** | 75.3 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Exceptional performance on MMLU benchmark (>90%), demonstrating strong general knowledge.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

718B-A39B. Trained on 6,000 Ascend NPUs (Kunpeng 920 processors in Huawei Atlas 800T A2 servers).

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/pangu-tech/pangu-ultra)
- 📄 [Technical Documentation](https://arxiv.org/abs/2505.04519)

## 🔍 Related Models

**From Huawei:**
- See all models in [Huawei profile](../../labs/huawei.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Huawei Models](../../labs/huawei.md)
