# Qwen3-235B-A22B-Thinking-2507

> Reasoning

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Jul/2025
**Access:** 🟢 Public

---

## 📊 Overview

Qwen3-235B-A22B-Thinking-2507 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 235.0B
- **Training Tokens:** 36000.0B
- **Token:Param Ratio:** 154:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 9.7 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 93.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | 84.4 | Advanced MMLU variant |
| **GPQA** | 81.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Exceptional performance on MMLU benchmark (>90%), demonstrating strong general knowledge.

**Analysis:** Outstanding reasoning performance on GPQA (>80%), approaching expert-level problem solving.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

235B-A22B. "Qwen3 is pre-trained on 36 trillion tokens across 119 languages" MMLU score is MMLU-Redux.

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/Qwen/Qwen3-235B-A22B-Thinking-2507)
- 📄 [Technical Documentation](https://huggingface.co/Qwen/Qwen3-235B-A22B-Thinking-2507)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
