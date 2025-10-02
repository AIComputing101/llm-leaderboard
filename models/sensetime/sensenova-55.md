# SenseNova 5.5

> Large Language Model

**Organization:** [SenseTime](../../labs/sensetime.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

SenseNova 5.5 is a large language model developed by SenseTime.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 600.0B
- **Training Tokens:** 10000.0B
- **Token:Param Ratio:** 17:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 8.2 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"The model training was based on over 10TB tokens [sic, taken as 10T tokens instead of 10TB=2T tokens] of high-quality training data, including a large amount of synthetically-generated reasoning chain data, which help to enhance its reasoning capabilities." & "The updates include SenseNova 5o, the first real-time multimodal model in China, which provides a new AI interaction model on par with GPT-4o’s streaming interaction capabilities"

## 🔗 Resources

- 🎮 [Try the Model](https://platform.sensenova.cn/home#/home)
- 📄 [Technical Documentation](https://www.sensetime.com/en/news-detail/51168278?categoryId=1072)

## 🔍 Related Models

**From SenseTime:**
- See all models in [SenseTime profile](../../labs/sensetime.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All SenseTime Models](../../labs/sensetime.md)
