# Hunyuan-A13B

> Large Language Model

**Organization:** [Tencent](../../labs/tencent.md)
**Released:** Jun/2025
**Access:** 🟢 Public

---

## 📊 Overview

Hunyuan-A13B is a large language model developed by Tencent.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 80.0B
- **Training Tokens:** 7000.0B
- **Token:Param Ratio:** 88:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.5 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 88.17 | General knowledge across 57 subjects |
| **MMLU-Pro** | 67.23 | Advanced MMLU variant |
| **GPQA** | 71.2 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

80B-A13B. 'We have open-sourced Hunyuan-A13B-Pretrain , Hunyuan-A13B-Instruct , Hunyuan-A13B-Instruct-FP8 , Hunyuan-A13B-Instruct-GPTQ-Int4 on Hugging Face.'

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/tencent/Hunyuan-A13B-Instruct)
- 📄 [Technical Documentation](https://huggingface.co/tencent/Hunyuan-A13B-Instruct)

## 🔍 Related Models

**From Tencent:**
- See all models in [Tencent profile](../../labs/tencent.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tencent Models](../../labs/tencent.md)
