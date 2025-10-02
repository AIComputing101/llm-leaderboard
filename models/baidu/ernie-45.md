# ERNIE 4.5

> Reasoning

**Organization:** [Baidu](../../labs/baidu.md)
**Released:** Mar/2025
**Access:** 🟢 Public

---

## 📊 Overview

ERNIE 4.5 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 424.0B
- **Training Tokens:** 16000.0B
- **Token:Param Ratio:** 38:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.7 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 79.0 | Advanced MMLU variant |
| **GPQA** | 55.0 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

424B-A47B. Announce: https://x.com/Baidu_Inc/status/1901094083508220035

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/baidu/ERNIE-4.5-VL-424B-A47B-PT)
- 📄 [Technical Documentation](https://www.prnewswire.com/news-releases/baidu-unveils-ernie-4-5-and-reasoning-model-ernie-x1--makes-ernie-bot-free-ahead-of-schedule-302402490.html)

## 🔍 Related Models

**From Baidu:**
- See all models in [Baidu profile](../../labs/baidu.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Baidu Models](../../labs/baidu.md)
