# gpt-oss-20b

> Reasoning, SOTA

**Organization:** [OpenAI](../../labs/openai.md)
**Released:** Aug/2025
**Access:** 🟢 Public

---

## 📊 Overview

gpt-oss-20b represents state-of-the-art performance in its category, with advanced reasoning capabilities.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 20.0B
- **Training Tokens:** 13000.0B
- **Token:Param Ratio:** 650:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.7 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 85.3 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 71.5 | Graduate-level reasoning |
| **HLE** | 17.3 | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`, `SOTA`

## 📝 Additional Notes

20.9B total and 3.6B active parameters. https://openai.com/index/introducing-gpt-oss/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/openai/gpt-oss-20b)
- 📄 [Technical Documentation](https://cdn.openai.com/pdf/419b6906-9da6-406c-a19d-1bb078ac7637/oai_gpt-oss_model_card.pdf)

## 🔍 Related Models

**From OpenAI:**
- See all models in [OpenAI profile](../../labs/openai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenAI Models](../../labs/openai.md)
