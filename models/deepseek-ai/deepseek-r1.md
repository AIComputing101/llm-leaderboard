# DeepSeek-R1

> Reasoning, SOTA

**Organization:** [DeepSeek-AI](../../labs/deepseek-ai.md)
**Released:** Jan/2025
**Access:** 🟢 Public

---

## 📊 Overview

DeepSeek-R1 represents state-of-the-art performance in its category, with advanced reasoning capabilities.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 685.0B
- **Training Tokens:** 14800.0B
- **Token:Param Ratio:** 22:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 10.6 (Very powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 90.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | 84.0 | Advanced MMLU variant |
| **GPQA** | 71.5 | Graduate-level reasoning |
| **HLE** | 8.6 | High-level evaluation |

**Analysis:** Exceptional performance on MMLU benchmark (>90%), demonstrating strong general knowledge.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`, `SOTA`

## 📝 Additional Notes

"DeepSeek-R1 achieves performance comparable to OpenAI-o1 across math, code, and reasoning tasks. To support the research community, we have open-sourced DeepSeek-R1-Zero, DeepSeek-R1, and six dense models distilled from DeepSeek-R1 based on Llama and Qwen. DeepSeek-R1-Distill-Qwen-32B outperforms OpenAI-o1-mini across various benchmarks"

## 🔗 Resources

- 🎮 [Try the Model](https://chat.deepseek.com/)
- 📄 [Technical Documentation](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf)

## 🔍 Related Models

**From DeepSeek-AI:**
- See all models in [DeepSeek-AI profile](../../labs/deepseek-ai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All DeepSeek-AI Models](../../labs/deepseek-ai.md)
