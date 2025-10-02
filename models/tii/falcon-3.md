# Falcon 3

> Large Language Model

**Organization:** [TII](../../labs/tii.md)
**Released:** Dec/2024
**Access:** 🟢 Public

---

## 📊 Overview

Falcon 3 is a large language model developed by TII.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 10.0B
- **Training Tokens:** 16000.0B
- **Token:Param Ratio:** 1,600:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.3 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 73.1 | General knowledge across 57 subjects |
| **MMLU-Pro** | 42.5 | Advanced MMLU variant |
| **GPQA** | 34.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

"We conducted a single large-scale pretraining run on the 7B model, using 1024 H100 GPU chips, leveraging 14 trillion tokens... upscaled the 7B model to a 10B parameters model by duplicating the redundant layers and continuing pre-training with 2 trillion tokens of high-quality data."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/tiiuae/Falcon3-10B-Base)
- 📄 [Technical Documentation](https://huggingface.co/blog/falcon3)

## 🔍 Related Models

**From TII:**
- See all models in [TII profile](../../labs/tii.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All TII Models](../../labs/tii.md)
