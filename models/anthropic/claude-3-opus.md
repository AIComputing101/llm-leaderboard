# Claude 3 Opus

> SOTA

**Organization:** [Anthropic](../../labs/anthropic.md)
**Released:** Mar/2024
**Access:** 🟢 Public

---

## 📊 Overview

Claude 3 Opus represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 2500.0B
- **Training Tokens:** 40000.0B
- **Token:Param Ratio:** 16:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 33.3 (Extremely powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 86.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | 68.5 | Advanced MMLU variant |
| **GPQA** | 59.5 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Original MMLU=86.8 (GPT-4=86.4). MMLU=88.2 with CoT prompting. Original GPQA=50.4. 200k context, 1M for researchers.

## 🔗 Resources

- 🎮 [Try the Model](https://claude.ai/)
- 📄 [Technical Documentation](https://www.anthropic.com/claude-3-model-card)

## 🔍 Related Models

**From Anthropic:**
- See all models in [Anthropic profile](../../labs/anthropic.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Anthropic Models](../../labs/anthropic.md)
