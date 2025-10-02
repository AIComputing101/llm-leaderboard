# MiniMax-Text-01

> Large Language Model

**Organization:** [MiniMax](../../labs/minimax.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

MiniMax-Text-01 is a large language model developed by MiniMax.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 456.0B
- **Training Tokens:** 7200.0B
- **Token:Param Ratio:** 16:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 6.0 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 88.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | 75.7 | Advanced MMLU variant |
| **GPQA** | 54.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

A45.9B. "The pre-training corpus for MiniMax-Text-01 encompasses a comprehensive and meticulously curated dataset, incorporating diverse sources including academic literature, books, web content, and programming code... repeatedly training high-quality documents can lead to enhanced downstream performance, with certain high-quality domains being trained up to 50 times... Our findings indicate that low-quality data suffer a substantial decrease in performance after training for more than two epochs, while high-quality data can be effectively trained for up to four epochs" Login playground: https://www.hailuo.ai/

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/MiniMax-AI/MiniMax-01)
- 📄 [Technical Documentation](https://arxiv.org/abs/2501.08313)

## 🔍 Related Models

**From MiniMax:**
- See all models in [MiniMax profile](../../labs/minimax.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All MiniMax Models](../../labs/minimax.md)
