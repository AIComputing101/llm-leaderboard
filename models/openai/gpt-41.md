# GPT-4.1

> SOTA

**Organization:** [OpenAI](../../labs/openai.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

GPT-4.1 represents state-of-the-art performance in its category.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 300.0B
- **Training Tokens:** 20000.0B
- **Token:Param Ratio:** 67:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 8.2 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 90.2 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 66.3 | Graduate-level reasoning |
| **HLE** | 5.4 | High-level evaluation |

**Analysis:** Exceptional performance on MMLU benchmark (>90%), demonstrating strong general knowledge.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`SOTA`

## 📝 Additional Notes

Outperforms GPT‑4o "across the board, with major gains in coding and instruction following. They also have larger context windows—supporting up to 1 million tokens of context—and are able to better use that context with improved long-context comprehension. They feature a refreshed knowledge cutoff of June 2024."

## 🔗 Resources

- 🎮 [Try the Model](https://platform.openai.com/playground/p/HqaxY9MEZ8Ta0zFbzfASn5bJ?mode=chat)
- 📄 [Technical Documentation](https://openai.com/index/gpt-4-1/)

## 🔍 Related Models

**From OpenAI:**
- See all models in [OpenAI profile](../../labs/openai.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All OpenAI Models](../../labs/openai.md)
