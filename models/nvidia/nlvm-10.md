# NLVM 1.0

> Large Language Model

**Organization:** [NVIDIA](../../labs/nvidia.md)
**Released:** Sep/2024
**Access:** 🟢 Public

---

## 📊 Overview

NLVM 1.0 is a large language model developed by NVIDIA.

## 🔧 Technical Specifications

### Model Architecture
- **Type:** Dense
- **Parameters:** 72.0B
- **Training Tokens:** 18000.0B
- **Token:Param Ratio:** 250:1 ✅ Compute-optimal

### Training Efficiency
- **ALScore:** 3.8 (Mid-tier)
- **Formula:** √(Parameters × Tokens) ÷ 300

### Training Data
- **Dataset Type:** web-scale

## 📈 Performance Benchmarks

| Benchmark | Score | Description |
|-----------|-------|-------------|
| **MMLU** | 82.0 | General knowledge across 57 subjects |
| **MMLU-Pro** | - | Advanced MMLU variant |
| **GPQA** | - | Graduate-level reasoning |
| **HLE** | - | High-level evaluation |

**Analysis:** Strong performance on MMLU benchmark (80-90%), indicating solid general capabilities.

## 🏷️ Model Tags

_No specific tags_

## 📝 Additional Notes

Flamingo clone. "we use Qwen2-72B-Instruct as the default text-only LLM backbone. We also employ Nous-Hermes-2-Yi-34B for ablation study and faster experimentation... we use InternViT-6B as the default vision encoder"

## 🔗 Resources

- 🎮 [Try the Model](https://huggingface.co/nvidia/NVLM-D-72B)
- 📄 [Technical Documentation](https://arxiv.org/abs/2409.11402)

## 🔍 Related Models

**From NVIDIA:**
- See all models in [NVIDIA profile](../../labs/nvidia.md)

**Similar Architecture:**
- See all [Dense models](../../architectures/dense.md)

---

**Last Updated:** 2025-10-02

[← Back to Leaderboard](../../README.md) • [View All NVIDIA Models](../../labs/nvidia.md)
