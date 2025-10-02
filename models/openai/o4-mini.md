# o4-mini

> Reasoning, SOTA

**Organization:** [OpenAI](../../labs/openai.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

o4-mini represents state-of-the-art performance in its category, with advanced reasoning capabilities.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 200.0B
- **Training Tokens:** 40000.0B
- **Token:Param Ratio:** 200:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 9.4 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 88.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 81.4 | Graduate-level reasoning |
| **HLE** | 14.28 | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Outstanding reasoning performance on GPQA (>80%), approaching expert-level problem solving.

## 🏷️ Model Tags

`Reasoning`, `SOTA`

## 📝 Additional Notes

https://openai.com/index/introducing-o3-and-o4-mini/ MMLU shows a translated LOTE.

## 🔗 Resources

- 🎮 [Try the Model](https://chatgpt.com/?model=o4-mini-high)
- 📄 [Technical Documentation](https://cdn.openai.com/pdf/2221c875-02dc-4789-800b-e7758f3722c1/o3-and-o4-mini-system-card.pdf)

## 🔍 Related Models

**From OpenAI:**
- See all models in [OpenAI profile](../../labs/openai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenAI Models](../../labs/openai.md)
