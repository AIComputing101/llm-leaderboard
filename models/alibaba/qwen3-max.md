# Qwen3-Max

> Reasoning

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

Qwen3-Max is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 1000.0B
- **Training Tokens:** 36000.0B
- **Token:Param Ratio:** 36:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 20.0 (Extremely powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 85.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Outstanding reasoning performance on GPQA (>80%), approaching expert-level problem solving.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"Qwen3-Max-Thinking — still under active training — is already demonstrating remarkable potential. When augmented with tool usage and scaled test-time compute, the Thinking variant has achieved 100% on challenging reasoning benchmarks such as AIME 25 and HMMT. "

## 🔗 Resources

- 🎮 [Try the Model](https://chat.qwen.ai/)
- 📄 [Technical Documentation](https://qwen.ai/blog?id=241398b9cd6353de490b0f82806c7848c5d2777d&from=research.latest-advancements-list)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
