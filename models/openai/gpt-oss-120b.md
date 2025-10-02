# gpt-oss-120b

> Reasoning, SOTA

**Organization:** [OpenAI](../../labs/openai.md)
**Released:** Aug/2025
**Access:** 🟢 Public

---

## 📊 Overview

gpt-oss-120b represents state-of-the-art performance in its category, with advanced reasoning capabilities.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 120.0B
- **Training Tokens:** 30000.0B
- **Token:Param Ratio:** 250:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 6.3 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 90.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 80.1 | Graduate-level reasoning |
| **HLE** | 19.0 | High-level evaluation |

**Analysis:** Exceptional performance on MMLU benchmark (>90%), demonstrating strong general knowledge.

**Analysis:** Outstanding reasoning performance on GPQA (>80%), approaching expert-level problem solving.

## 🏷️ Model Tags

`Reasoning`, `SOTA`

## 📝 Additional Notes

116.8B total parameters and 5.1B “active” parameters per token per forward pass. https://openai.com/index/introducing-gpt-oss/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/openai/gpt-oss-120b)
- 📄 [Technical Documentation](https://cdn.openai.com/pdf/419b6906-9da6-406c-a19d-1bb078ac7637/oai_gpt-oss_model_card.pdf)

## 🔍 Related Models

**From OpenAI:**
- See all models in [OpenAI profile](../../labs/openai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenAI Models](../../labs/openai.md)
