# Qwen3-235B-A22B

> Reasoning

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Apr/2025
**Access:** 🟢 Public

---

## 📊 Overview

Qwen3-235B-A22B is designed for advanced reasoning and multi-step problem solving.

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
| **MMLU** | 87.81 | General knowledge across 57 subjects |
| **MMLU-Pro** | 68.18 | Advanced MMLU variant |
| **GPQA** | 47.47 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Qwen3-235B-A22B. Qwen3-30B-A3B. "Qwen3 is pre-trained on 36 trillion tokens across 119 languages"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/Qwen/Qwen3-235B-A22B)
- 📄 [Technical Documentation](https://github.com/QwenLM/Qwen3/blob/main/Qwen3_Technical_Report.pdf)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
