# Grok-1.5

> Large Language Model

**Organization:** [xAI](../../labs/xai.md)
**Released:** Mar/2024
**Access:** 🟢 Public

---

## 📊 Overview

Grok-1.5 is a large language model developed by xAI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 180.0B
- **Training Tokens:** 6000.0B
- **Token:Param Ratio:** 34:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 81.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Context=128k.

## 🔗 Resources

- 🎮 [Try the Model](https://grok.x.ai/)
- 📄 [Technical Documentation](https://x.ai/blog/grok-1.5)

## 🔍 Related Models

**From xAI:**
- See all models in [xAI profile](../../labs/xai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All xAI Models](../../labs/xai.md)
