# Qwen3-Omni

> Reasoning

**Organization:** [Alibaba](../../labs/alibaba.md)
**Released:** Sep/2025
**Access:** 🟢 Public

---

## 📊 Overview

Qwen3-Omni is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 30.0B
- **Training Tokens:** 17000.0B
- **Token:Param Ratio:** 567:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 2.4 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 88.8 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | 73.1 | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

**Analysis:** Good reasoning capabilities on GPQA (60-80%).

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"Qwen3-Omni is a unified end-to-end model capable of processing multiple modalities, such as text, audio, image and video, and generating real-time text or speech response."... "pretraining utilizes a large-scale dataset containing approximately 2 trillion tokens, with the following distribution across modalities: text (0.57 trillion), audio (0.77 trillion), image (0.82 trillion), video (0.05 trillion), and video-audio (0.05 trillion)."

## 🔗 Resources

- 🎮 [Try the Model](https://github.com/QwenLM/Qwen3-Omni?tab=readme-ov-file)
- 📄 [Technical Documentation](https://github.com/QwenLM/Qwen3-Omni/blob/main/assets/Qwen3_Omni.pdf)

## 🔍 Related Models

**From Alibaba:**
- See all models in [Alibaba profile](../../labs/alibaba.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All Alibaba Models](../../labs/alibaba.md)
