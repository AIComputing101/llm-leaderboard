# MGIE

> Diffusion

**Organization:** [Apple](../../labs/apple.md)
**Released:** Jan/2024
**Access:** 🟢 Public

---

## 📊 Overview

MGIE is a large language model developed by Apple.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 7.0B
- **Training Tokens:** 2000.0B
- **Token:Param Ratio:** 286:1 ✅ Compute-optimal

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

`Diffusion`

## 📝 Additional Notes

MLLM and diffusion model initialized from LLaVA-7B (Llama 2 + Vicuna) + StableDiffusion-v1.5.

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/tsujuifu/pytorch_mgie)
- 📄 [Technical Documentation](https://openreview.net/forum?id=S1RKWSyZ2Y)

## 🔍 Related Models

**From Apple:**
- See all models in [Apple profile](../../labs/apple.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Apple Models](../../labs/apple.md)
