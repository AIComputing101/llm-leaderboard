# LLaMA Pro

> Large Language Model

**Organization:** [Tencent](../../labs/tencent.md)
**Released:** Jan/2024
**Access:** 🟢 Public

---

## 📊 Overview

LLaMA Pro is a large language model developed by Tencent.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 8.3B
- **Training Tokens:** 2080.0B
- **Token:Param Ratio:** 251:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | - | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

We pre-train LLAMA PRO’s expanded blocks on 80B tokens using open-source code and math data for 2830 GPU Hours (16 NVIDIA H800 GPUs for about 7 days).

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/TencentARC/LLaMA-Pro-8B)
- 📄 [Technical Documentation](https://arxiv.org/abs/2401.02415)

## 🔍 Related Models

**From Tencent:**
- See all models in [Tencent profile](../../labs/tencent.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Tencent Models](../../labs/tencent.md)
