# Granite-4.0-Tiny-Preview

> Reasoning

**Organization:** [IBM](../../labs/ibm.md)
**Released:** May/2025
**Access:** 🟢 Public

---

## 📊 Overview

Granite-4.0-Tiny-Preview is designed for advanced reasoning and multi-step problem solving.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** MoE
- **Parameters:** 7.0B
- **Training Tokens:** 2500.0B
- **Token:Param Ratio:** 358:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 0.4 (Lightweight)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** synthetic, web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 60.4 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

## 🏷️ Model Tags

`Reasoning`

## 📝 Additional Notes

"the model is only partially trained—it has only seen 2.5T of a planned 15T or more training tokens...Granite 4.0 Tiny-Preview, specifically, is a fine-grained hybrid mixture of experts (MoE) model, with 7B total parameters and only 1B active parameters at inference time... Like its predecessors in Granite 3.2 and Granite 3.3, Granite 4.0 Tiny Preview offers toggleable thinking on and thinking off functionality (though its reasoning-focused post-training is very much incomplete)."

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/ibm-granite/granite-4.0-tiny-preview)
- 📄 [Technical Documentation](https://www.ibm.com/new/announcements/ibm-granite-4-0-tiny-preview-sneak-peek)

## 🔍 Related Models

**From IBM:**
- See all models in [IBM profile](../../labs/ibm.md)

**Similar Architecture:**
- See all [MoE models](../../architectures/moe.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All IBM Models](../../labs/ibm.md)
