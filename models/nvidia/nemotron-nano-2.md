# Nemotron Nano 2

> Reasoning

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Aug/2025
**Access:** 🟢 Public

---

## 📊 Overview

Nemotron Nano 2 is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 12.31B
- **Training Tokens:** 20000.0B
- **Token:Param Ratio:** 1,625:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 1.7 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 78.24 | General knowledge across 57 subjects |
| **MMLU-Pro** | 63.98 | Advanced MMLU variant |
| **GPQA** | 64.48 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

Announce: https://research.nvidia.com/labs/adlr/NVIDIA-Nemotron-Nano-2/

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/nvidia/NVIDIA-Nemotron-Nano-12B-v2-Base)
- 📄 [Technical Documentation](https://research.nvidia.com/labs/adlr/files/NVIDIA-Nemotron-Nano-2-Technical-Report.pdf)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
