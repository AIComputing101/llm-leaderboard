# GPT-4 Classic (gpt-4-0314 & gpt-4-0613, non-Turbo)

> SOTA

**Organization:** [OpenAI](../../labs/openai.md)
**Released:** Mar/2023
**Access:** 🟢 Public

---

## 📊 Overview

GPT-4 Classic (gpt-4-0314 & gpt-4-0613, non-Turbo) represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 1760.0B
- **Training Tokens:** 13000.0B
- **Token:Param Ratio:** 8:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 15.9 (Very powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 86.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 35.7 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Original MMLU=86.4. MMLU=90.1 with prompting. Proto-AGI. 1.76T parameters MoE.

## 🔗 Resources

- 🎮 [Try the Model](https://chat.openai.com/)
- 📄 [Technical Documentation](https://cdn.openai.com/papers/gpt-4.pdf)

## 🔍 Related Models

**From OpenAI:**
- See all models in [OpenAI profile](../../labs/openai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenAI Models](../../labs/openai.md)
