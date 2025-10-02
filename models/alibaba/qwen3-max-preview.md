# Qwen3-Max-Preview

> Large Language Model

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

Qwen3-Max-Preview is a large language model developed by Alibaba.

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
| **GPQA** | 64.6 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

GPQA score is SuperGPQA. "our biggest model yet, with over 1 trillion parameters"

## 🔗 Resources

- 🎮 [Try the Model](https://chat.qwen.ai/)
- 📄 [Technical Documentation](https://modelstudio.console.alibabacloud.com/?tab=doc#/doc/?type=model&url=2840914_2&modelId=qwen3-max-preview)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
