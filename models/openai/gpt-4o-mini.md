# GPT-4o mini

> Large Language Model

**Organization:** [OpenAI](../../labs/openai.md)
**Released:** Jul/2024
**Access:** 🟢 Public

---

## 📊 Overview

GPT-4o mini is a large language model developed by OpenAI.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 8.0B
- **Training Tokens:** 13000.0B
- **Token:Param Ratio:** 1,625:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.1 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 82.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 40.2 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Omnimodel. "OpenAI would not disclose exactly how large GPT-4o mini is, but said it’s roughly in the same tier as other small AI models, such as Llama 3 8b, Claude Haiku and Gemini 1.5 Flash." https://techcrunch.com/2024/07/18/openai-unveils-gpt-4o-mini-a-small-ai-model-powering-chatgpt/ "tested GPT-4o to identify potential risks, which we have addressed and plan to share the details of in the forthcoming GPT-4o system card and Preparedness scorecard." And related paper about instruction hierarchy: https://arxiv.org/abs/2404.13208

## 🔗 Resources

- 🎮 [Try the Model](https://chatgpt.com/)
- 📄 [Technical Documentation](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/)

## 🔍 Related Models

**From OpenAI:**
- See all models in [OpenAI profile](../../labs/openai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenAI Models](../../labs/openai.md)
