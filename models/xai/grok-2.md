# Grok-2

> SOTA

**Organization:** [xAI](../../labs/xai.md)
**Released:** Aug/2024
**Access:** 🟢 Public

---

## 📊 Overview

Grok-2 represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 400.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 38:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.2 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 87.5 | General knowledge across 57 subjects |
| **MMLU-Pro** | 75.5 | Advanced MMLU variant |
| **GPQA** | 56.0 | Graduate-level reasoning |
| **HLE** | 3.9 | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

MMLU-Pro=75.5=SOTA. Claude 3.5S MMLU-Pro=72.83. "Grok-2 has been tested on the LMSYS leaderboard under the name "sus-column-r." At the time of this blog post, it is outperforming both Claude 3.5 Sonnet and GPT-4-Turbo." [Alan: Grok is Heinlein, Sixth Column is also Heinlein: https://en.wikipedia.org/wiki/Sixth_Column ]

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/xai-org/grok-2)
- 📄 [Technical Documentation](https://x.ai/blog/grok-2)

## 🔍 Related Models

**From xAI:**
- See all models in [xAI profile](../../labs/xai.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All xAI Models](../../labs/xai.md)
