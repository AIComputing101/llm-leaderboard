# MiMo-7B-RL-0530

> Reasoning

**Organization:** [Xiaomi](../../labs/xiaomi.md)
**Released:** May/2025
**Access:** 🟢 Public

---

## 📊 Overview

MiMo-7B-RL-0530 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 25000.0B
- **Token:Param Ratio:** 3,572:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.4 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 58.6 | Advanced MMLU variant |
| **GPQA** | 60.6 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"[2025.05.30] During the RL training, by continuously expanding the training window size (from 32K to 48K), the performance of MiMo-7B-RL-0530 on AIME24 can be continuously improved and eventually surpass that of DeepSeek R1... MiMo-7B-Base is pre-trained on approximately 25 trillion tokens."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/XiaomiMiMo/MiMo-7B-RL-0530)
- 📄 [Technical Documentation](https://arxiv.org/abs/2505.07608)

## 🔍 Related Models

**From Xiaomi:**
- See all models in [Xiaomi profile](../../labs/xiaomi.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Xiaomi Models](../../labs/xiaomi.md)
