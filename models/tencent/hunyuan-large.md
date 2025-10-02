# Hunyuan-Large

> Large Language Model

**Organization:** [Tencent](../../labs/tencent.md)
**Released:** Nov/2024
**Access:** 🟢 Public

---

## 📊 Overview

Hunyuan-Large is a large language model developed by Tencent.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 389.0B
- **Training Tokens:** 7000.0B
- **Token:Param Ratio:** 18:1 ⚠️ Under-trained

### Training Efficiency
- **ALScore:** 5.5 (Powerful)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 89.9 | General knowledge across 57 subjects |
| **MMLU-Pro** | 60.2 | Advanced MMLU variant |
| **GPQA** | 42.4 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Hunyuan-Large is pre-trained on 7T tokens, which contains nearly 1.5T tokens of high-quality and diverse synthetic data.' '389 billion parameters and 52 billion activation parameters, capable of handling up to 256K tokens'

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/tencent/Tencent-Hunyuan-Large)
- 📄 [Technical Documentation](https://arxiv.org/abs/2411.02265)

## 🔍 Related Models

**From Tencent:**
- See all models in [Tencent profile](../../labs/tencent.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tencent Models](../../labs/tencent.md)
