# MiniMax-M1

> Reasoning

**Organization:** [MiniMax](../../labs/minimax.md)
**Released:** Jun/2025
**Access:** 🟢 Public

---

## 📊 Overview

MiniMax-M1 is designed for advanced reasoning and multi-step problem solving.

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
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | 81.1 | Advanced MMLU variant |
| **GPQA** | 70.0 | Graduate-level reasoning |
| **HLE** | 8.4 | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

456B-A45.9B. Announce: https://www.minimax.io/news/minimaxm1

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/MiniMaxAI/MiniMax-M1-80k)
- 📄 [Technical Documentation](https://arxiv.org/abs/2506.13585)

## 🔍 Related Models

**From MiniMax:**
- See all models in [MiniMax profile](../../labs/minimax.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All MiniMax Models](../../labs/minimax.md)
