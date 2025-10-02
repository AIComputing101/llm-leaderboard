# Qwen3-Next-80B-A3B

> Reasoning

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

Qwen3-Next-80B-A3B is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 80.0B
- **Training Tokens:** 15000.0B
- **Token:Param Ratio:** 188:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.7 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 84.72 | General knowledge across 57 subjects |
| **MMLU-Pro** | 66.05 | Advanced MMLU variant |
| **GPQA** | 43.43 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"Qwen3-Next introduces several key improvements: a hybrid attention mechanism, a highly sparse Mixture-of-Experts (MoE) structure, training-stability-friendly optimizations, and a multi-token prediction mechanism for faster inference."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/collections/Qwen/qwen3-next-68c25fd6838e585db8eeea9d)
- 📄 [Technical Documentation](https://qwen.ai/blog?id=4074cca80393150c248e508aa62983f9cb7d27cd&from=research.latest-advancements-list)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
